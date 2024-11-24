<template>
  <MDBCard>
    <MDBCardBody>
      <form>
        <MDBRow tag="form" class="gy-2 gx-3 align-items-center">
          <MDBCol auto>
            <!-- Email input -->
            <MDBInput label="Email input" type="email" />
          </MDBCol>
          <MDBCol auto>
            <!-- Submit button -->
            <MDBBtn color="primary" block class="mb-4"> Subscribe </MDBBtn>
          </MDBCol>
        </MDBRow>
      </form>
    </MDBCardBody>
  </MDBCard>
</template>

<script setup lang="ts">
import {
  MDBInput,
  MDBCheckbox,
  MDBBtn,
  MDBCardBody,
  MDBCard
} from "mdb-vue-ui-kit";
import { ref } from "vue";

const form5Name = ref("");
const form5Email = ref("");
const form5TermsCheck = ref(true);
</script>

<style>
body {
  background-color: #ffd8bd;
}
</style>