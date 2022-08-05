<template>
  <div>
    <nav class="bg-white ">
      <div class="container px-6 py-4 mx-auto">
        <div class="md:flex md:items-center md:justify-between">
          <div class="flex items-center justify-between">
            <div class="text-xl font-semibold text-gray-700">
              <div
                class="f-outline px-2 relative focus-within:border-green-300"
                style="display: flex; align-items: center"
              >
                <svg
                  width="20"
                  height="20"
                  viewBox="0 0 20 20"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M12.9167 11.6667H12.2583L12.025 11.4417C12.8417 10.4917 13.3333 9.25833 13.3333 7.91667C13.3333 4.925 10.9083 2.5 7.91667 2.5C4.925 2.5 2.5 4.925 2.5 7.91667C2.5 10.9083 4.925 13.3333 7.91667 13.3333C9.25833 13.3333 10.4917 12.8417 11.4417 12.025L11.6667 12.2583V12.9167L15.8333 17.075L17.075 15.8333L12.9167 11.6667V11.6667ZM7.91667 11.6667C5.84167 11.6667 4.16667 9.99167 4.16667 7.91667C4.16667 5.84167 5.84167 4.16667 7.91667 4.16667C9.99167 4.16667 11.6667 5.84167 11.6667 7.91667C11.6667 9.99167 9.99167 11.6667 7.91667 11.6667Z"
                    fill="#5B63A9"
                  />
                </svg>

                <input
                  type="search"
                  name="search"
                  placeholder="Search for any training"
                  class="
                    block
                    p-2
                    w-full
                    text-sm
                    appearance-none
                    focus:outline-none
                    bg-transparent
                  "
                />
              </div>
            </div>

            <!-- Mobile menu button -->
            <div class="flex md:hidden">
              <button
                type="button"
                class="
                  text-gray-500
                  dark:text-gray-200
                  hover:text-gray-600
                  dark:hover:text-gray-400
                  focus:outline-none focus:text-gray-600
                  dark:focus:text-gray-400
                "
                aria-label="toggle menu"
              >
                <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                  <path
                    fill-rule="evenodd"
                    d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"
                  ></path>
                </svg>
              </button>
            </div>
          </div>

          <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
          <div class="flex-1 md:flex md:items-center md:justify-between">
            <div
              class="flex flex-col -mx-4 md:flex-row md:items-center md:mx-8"
            ></div>

            <div class="flex items-center mt-4 md:mt-0">
              <button
                class="
                  hidden
                  mx-4
                  text-gray-600
                  transition-colors
                  duration-200
                  transform
                  md:block
                  dark:text-gray-200
                  hover:text-gray-700
                  dark:hover:text-gray-400
                  focus:text-gray-700
                  dark:focus:text-gray-400
                  focus:outline-none
                "
                
              >
                <svg
                  width="16"
                  height="20"
                  viewBox="0 0 16 20"
                  fill="none"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M15.5 16.2071V16.5H0.5V16.2071L2.35355 14.3536L2.5 14.2071V14V9C2.5 6.09437 4.02219 3.78092 6.61528 3.16653L7 3.07538V2.68V2C7 1.44614 7.44614 1 8 1C8.55386 1 9 1.44614 9 2V2.68V3.07506L9.38434 3.16644C11.9681 3.78076 13.5 6.10482 13.5 9V14V14.2071L13.6464 14.3536L15.5 16.2071ZM9.41352 18.5C9.20605 19.0806 8.64884 19.5 8 19.5C7.34433 19.5 6.79074 19.0813 6.58536 18.5H9.41352Z"
                    fill="white"
                    stroke="#C2CFE0"
                  />
                </svg>
              </button>

              <button
                type="button"
                class="flex items-center focus:outline-none"
                aria-label="toggle profile dropdown"
              >
                <div
                  class="
                    w-8
                    h-8
                    overflow-hidden
                    border-2
                    rounded-full
                  "
                  style="border-color: #FD648E"
                >
                  <img
                    src="https://images.unsplash.com/photo-1517841905240-472988babdf9?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80"
                    class="object-cover w-full h-full"
                    alt="avatar"
                  />
                </div>
              </button>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>