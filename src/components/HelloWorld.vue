<template>
<form class="row g-3">
  <div class="col-md-5">
    <label for="inputName" class="form-label">FIRST NAME*</label>
    <input type="text" class="form-control" id="inputName">
  </div>
  <div class="col-md-5">
    <label for="inputGender" class="form-label">GENDER*</label>
    <input type="text" class="form-control" id="inputGender">
  </div>
  <div class="col-md-5">
    <label for="inputAddress" class="form-label">LAST NAME*</label>
    <input type="text" class="form-control" id="inputAddress">
  </div>
  <div class="col-md-5">
    <label for="inputAddress2" class="form-label">PAYMENT MODE*</label>
    <div class="select">
    <div class="form-check">
  <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault1">
  <label class="form-check-label" for="flexRadioDefault1">
    Visa
  </label>
</div>
<div class="form-check">
  <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault2" checked>
  <label class="form-check-label" for="flexRadioDefault2">
    Mastercard
  </label>
</div>
<div class="form-check">
  <input class="form-check-input" type="radio" name="flexRadioDefault" id="flexRadioDefault3" checked>
  <label class="form-check-label" for="flexRadioDefault3">
    Amex
  </label>
</div>
</div>
  </div>
  <div class="col-md-5">
    <label for="inputCity" class="form-label">COMPANY*</label>
    <input type="text" class="form-control" id="inputCity">
  </div>
  <div class="col-md-5">
    <label for="inputState" class="form-label">CARD NUMBER*</label>
    <input type="number" class="form-control" id="inputZip">
  </div>
  <div class="col-md-5">
    <label for="inputZip" class="form-label">EMAIL*</label>
    <input type="email" class="form-control" id="inputZip">
  </div>
  <div class="col-md-5">
    <label for="inputZip" class="form-label">EXPIRATION*</label>
    <input type="text" class="form-control" id="inputZip">
  </div>
  <div class="col-md-5">
    <label for="inputZip" class="form-label">PHONE NUMBER*</label>
    <input type="number" class="form-control" id="inputZip">
  </div>
  <div class="col-md-5">
    <label for="inputZip" class="form-label">CVN*</label>
    <input type="number" class="form-control" id="inputZip">
  </div>
  <div class="col-md-10">
  <label for="customRange1" class="form-label">Donate Us*</label>
  <input type="range" class="form-range" id="customRange1">
  </div>
  <div class="col-md-5">
    <button type="submit" class="btn btn-primary">Submit</button>
    <button type="reset" class="btn btn-primary">Reset</button>
  </div>
</form>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>
<style>
  .select {
display: flex;
  }
  </style>