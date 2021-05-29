<template>
  <div id="app">
    <!-- <BuefyForm /> -->
    <RefactoredForm />
  </div>
</template>

<script>
import Form from "./components/Form";
import RefactoredForm from "./components/RefactoredForm";

export default {
  name: "App",
  components: {
    BuefyForm: Form,
    RefactoredForm
  }
};
</script>
