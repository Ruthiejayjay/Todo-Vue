<template>
  <div class="w-full mt-16 md:mt-0 md:w-2/5">
    <form
      class="
        relative
        z-10
        h-auto
        p-8
        py-10
        overflow-hidden
        bg-white
        border-b-2 border-gray-300
        rounded-lg
        shadow-2xl
        px-7
      "
    >
      <h3 class="mb-6 text-2xl font-medium text-center">Add A New Todo</h3>
      <input
        type="text"
        name="name"
        class="
          block
          w-full
          px-4
          py-3
          mb-4
          border border-2 border-transparent border-gray-200
          rounded-lg
          focus:ring focus:ring-blue-500 focus:outline-none
        "
        placeholder="Enter New Todo"
      />
      <input
        type="datetime-local"
        name="reminderAt"
        class="
          block
          w-full
          px-4
          py-3
          mb-4
          border border-2 border-transparent border-gray-200
          rounded-lg
          focus:ring focus:ring-blue-500 focus:outline-none
        "
        placeholder=""
      />
      <div class="form-check mb-3">
        <input
          class="
            form-check-input
            appearance-none
            h-4
            w-4
            border border-gray-300
            rounded-sm
            bg-white
            checked:bg-blue-600 checked:border-blue-600
            focus:outline-none
            transition
            duration-200
            mt-1
            align-top
            bg-no-repeat bg-center bg-contain
            float-left
            mr-2
            cursor-pointer
          "
          type="checkbox"
          value=""
          id="flexCheckDefault"
        />
        <label
          class="form-check-label inline-block text-gray-800"
          for="flexCheckDefault"
        >
          Set Reminder
        </label>
      </div>
      <div class="block">
        <button
          class="w-full px-3 py-4 font-medium text-white bg-blue-600 rounded-lg"
        >
          Save Todo
        </button>
      </div>
    </form>
  </div>
</template>

<script>
export default {
    props: []
};
</script>

<style>
</style>