<template>
  <div class="flex flex-col items-center">
    <div class="flex-grow container mx-auto sm:px-4 pt-6 pb-8">
      <div class="bg-white sm:rounded shadow mb-6">
        <div class="px-6 py-3 bg-blue w-2/3 sm:w-1/4">
          <h1 class="text-light-normal sm:text-2xl sm:font-semibold ">
            Loan Application Form
          </h1>
        </div>
        <div class="p-6 w-full space-y-5 sm:space-y-10">
          <div>
            <label class="block mt-4">
              <span class="text-gray-hard">Loan Type</span>
              <select class="form-select mt-1 block w-full">
                <option>Car Loan</option>
                <option>Payday Loan</option>
                <option>$10,000</option>
                <option>$25,000</option>
              </select>
            </label>
          </div>
          <div
            class="flex flex-wrap flex-row sm:flex-no-wrap justify-between  space-x-0 space-y-5 sm:space-y-0 sm:space-x-4"
          >
            <div class="w-full">
              <label class="block">
                <span class="text-gray-hard">Last Name</span>
                <input class="form-input mt-1 w-full" placeholder="Jane Doe" />
              </label>
            </div>
            <div class="w-full">
              <label class="block">
                <span class="text-gray-hard">First Name</span>
                <input class="form-input mt-1 w-full" placeholder="Jane Doe" />
              </label>
            </div>
            <div class="w-full">
              <label class="block">
                <span class="text-gray-hard">Middle Name</span>
                <input class="form-input mt-1 w-full" placeholder="Jane Doe" />
              </label>
            </div>
          </div>

          <div class="mt-4">
            <span class="text-gray-hard">Account Type</span>
            <div class="mt-2">
              <label class="inline-flex items-center">
                <input
                  type="radio"
                  class="form-radio"
                  name="accountType"
                  value="personal"
                />
                <span class="ml-2">Personal</span>
              </label>
              <label class="inline-flex items-center ml-6">
                <input
                  type="radio"
                  class="form-radio"
                  name="accountType"
                  value="busines"
                />
                <span class="ml-2">Business</span>
              </label>
            </div>
          </div>

          <label class="block mt-4">
            <span class="text-gray-hard">Requested Limit</span>
            <select class="form-select mt-1 block w-full">
              <option>$1,000</option>
              <option>$5,000</option>
              <option>$10,000</option>
              <option>$25,000</option>
            </select>
          </label>

          <div class="flex mt-6">
            <label class="flex items-center">
              <input type="checkbox" class="form-checkbox" />
              <span class="ml-2"
                >I agree to the
                <span class="underline">privacy policy</span></span
              >
            </label>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Forms"
};
</script>
