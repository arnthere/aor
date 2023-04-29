<template>
  <div class="row">
    <h1 class="h3 mb-3">Send Emails</h1>
    <div class="row">
      <div class="col col-7 c-padding-1">
        <div class="row">
          <div class="col">
            <div>
              <select class="form-select mb-3">
                <option selected>Open this select menu</option>
                <option>One</option>
                <option>Two</option>
                <option>Three</option>
              </select>
            </div>
          </div>
          <div class="col">
            <div>
              <select class="form-select mb-4">
                <option selected>Open this select menu</option>
                <option>One</option>
                <option>Two</option>
                <option>Three</option>
              </select>
            </div>
          </div>
        </div>
        <div class="card">
          <div class="card-header">
            <h5 class="card-title mb-0">Empty card</h5>
          </div>
          <div class="card-body">
            <div class="c-width-1 email-form-format">
              <div class="d-flex">
                <label for="sendTo" class="col-sm-2">To:</label>
                <input id="sendTo" type="text" class="form-control col-sm-4" />
              </div>
            </div>
            <div class="c-width-1 email-form-format">
              <div class="d-flex">
                <label for="cc" class="col-sm-2">CC:</label>
                <input id="cc" type="text" class="form-control col-sm-4" />
              </div>
            </div>
            <div class="c-width-1 email-form-format">
              <div class="d-flex">
                <label for="subject" class="col-sm-2">Subject:</label>
                <input id="subject" type="text" class="form-control col-sm-4" />
              </div>
            </div>
            <div class="email-form-format">
              <div>
                <textarea
                  class="form-control"
                  rows="2"
                  placeholder="Message"
                ></textarea>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="col col-2">
        <div class="card">
          <div class="card-header">
            <h5 class="card-title mb-0">Empty card</h5>
          </div>
          <div class="card-body">
            <div>
              <label class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  value="option1"
                  name="radios-example"
                  checked
                />
                <span class="form-check-label"> Single Delivery </span>
              </label>
              <label class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  value="option2"
                  name="radios-example"
                />
                <span class="form-check-label"> Bulk Delivery </span>
              </label>
              <label class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  value="option3"
                  name="radios-example"
                />
                <span class="form-check-label"> Scheduled Delivery </span>
              </label>
            </div>
          </div>
        </div>
      </div>
      <div class="col col-3">
        <div class="card">
          <div class="card-header">
            <h5 class="card-title mb-0">Empty card</h5>
          </div>
          <div class="card-body">
            <button class="btn btn-info">Submit</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
export default {
  name: "HomeView",
};
</script>
<style scoped>
/* .c-padding-1 {
  padding: 10px 250px 10px 0px;
} */
.c-width-1 {
  width: inherit;
}
.email-form-format > div {
  padding: 5px 0px;
}
.email-form-format input[type="text"] {
  width: 83.4%;
}
textarea.form-control {
  height: 200px;
}
</style>
