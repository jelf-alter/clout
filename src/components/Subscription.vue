<template>
  <MDBCard>
    <MDBCardBody>
  <form>
    <MDBRow tag="form" class="gy-2 gx-3 align-items-center">
        <MDBCol auto>
            <!-- Name input -->
            <MDBInput
                type="text"
                label="Name"
                id="form5Name"
                v-model="form5Name"
                wrapperClass="mb-4"
            />
        </MDBCol>
        <MDBCol auto>
            <!-- Email input -->
            <MDBInput
                type="email"
                label="Email address"
                id="form5Email"
                v-model="form5Email"
                wrapperClass="mb-4"
            />
        </MDBCol>
        <MDBCol auto>
            <!-- Checkbox -->
            <MDBCheckbox
                label="I have read and agree to the terms"
                id="form5TermsCheck"
                v-model="form5TermsCheck"
                wrapperClass="d-flex justify-content-center mb-4"
            />
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