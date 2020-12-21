<template>
  <div class="min-h-screen bg-gray-100">
    <header class="bg-gray-800">
      <div class="container mx-auto px-6">
        <nav class="h-14 flex items-center justify-between">
          <div class="flex items-center space-x-6">
            <a href="#">
              <svg
                class="h-8 w-8 text-indigo-400"
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                stroke="currentColor"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z"
                />
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z"
                />
              </svg>
            </a>
            <div class="flex items-center space-x-4">
              <a
                href="#"
                class="px-3 py-2 text-sm font-medium leading-none text-white"
                >Dashboard</a
              >
              <a
                href="#"
                class="px-3 py-2 text-sm font-medium leading-none text-white"
                >Jobs</a
              >
              <a
                href="#"
                class="px-3 py-2 text-sm font-medium leading-none text-white"
                >Applicants</a
              >
              <a
                href="#"
                class="px-3 py-2 text-sm font-medium leading-none text-white"
                >Company</a
              >
            </div>
          </div>
          <div class="flex items-center space-x-8">
            <div class="relative text-gray-600 focus-within:text-gray-400">
              <span class="absolute inset-y-0 left-0 pl-3 flex items-center">
                <svg class="h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
                  <path
                    fill-rule="evenodd"
                    clip-rule="evenodd"
                    d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                  />
                </svg>
              </span>
              <input
                class="h-9 pl-11 text-sm rounded-md text-white bg-gray-900 focus:outline-none focus:text-gray-900 focus:bg-white"
                type="text"
                placeholder="Search"
              />
            </div>
            <button>
              <svg
                class="h-6 w-6 text-gray-400"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zM10 18a3 3 0 01-3-3h6a3 3 0 01-3 3z"
                />
              </svg>
            </button>
            <button>
              <img
                class="h-8 w-8 rounded-full"
                src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
                alt=""
              />
            </button>
          </div>
        </nav>
      </div>
    </header>
    <main>
      <div class="bg-white shadow">
        <div class="container mx-auto px-6">
          <div class="flex items-center justify-between py-5">
            <div class="space-y-3">
              <div>
                <a
                  href="#"
                  class="inline-flex items-center text-sm text-gray-500 leading-none"
                  ><svg
                    class="h-6 w-6 text-gray-400"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M12.707 5.293a1 1 0 010 1.414L9.414 10l3.293 3.293a1 1 0 01-1.414 1.414l-4-4a1 1 0 010-1.414l4-4a1 1 0 011.414 0z"
                      clip-rule="evenodd"
                    />
                  </svg>
                  <span>
                    Back-end Developer
                  </span>
                </a>
              </div>
              <div class="flex items-center space-x-4">
                <img
                  class="h-12 w-12 rounded-full"
                  src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
                  alt=""
                />
                <h1 class="text-3xl font-extrabold text-gray-900">
                  Ricardo Cooper
                </h1>
              </div>
            </div>
            <div class="flex items-center space-x-6">
              <div class="flex space-x-3">
                <button
                  class="h-9 px-3 border border-gray-200 text-sm font-medium rounded-md text-gray-700 shadow-sm"
                >
                  Disqualify
                </button>
                <button
                  class="h-9 px-3 text-sm font-medium rounded-md text-white bg-indigo-600 shadow-sm"
                >
                  Advance to offer
                </button>
              </div>
              <div class="flex space-x-4">
                <button>
                  <svg
                    class="h-6 w-6 text-gray-500"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </button>
                <button>
                  <svg
                    class="h-6 w-6 text-gray-500"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 20 20"
                    fill="currentColor"
                  >
                    <path
                      fill-rule="evenodd"
                      d="M14.707 12.707a1 1 0 01-1.414 0L10 9.414l-3.293 3.293a1 1 0 01-1.414-1.414l4-4a1 1 0 011.414 0l4 4a1 1 0 010 1.414z"
                      clip-rule="evenodd"
                    />
                  </svg>
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Main container area -->
      <div class="container mx-auto px-6 py-6">
        <div class="grid grid-cols-3 gap-5">
          <div class="col-span-2">
            <div>
              <h2 class="text-lg font-medium text-gray-900">Overview</h2>
              <div class="mt-4 bg-white rounded-md shadow overflow-hidden">
                <div class="px-6 py-6">
                  <dl class="grid grid-cols-2 gap-8">
                    <div>
                      <dt class="text-sm font-medium text-gray-500">
                        Application for
                      </dt>
                      <dt class="mt-2 text-base font-normal text-gray-900">
                        Back-end developer
                      </dt>
                    </div>
                    <div>
                      <dt class="text-sm font-medium text-gray-500">
                        Salary Expectation
                      </dt>
                      <dt class="mt-2 text-base font-normal text-gray-900">
                        $120,000
                      </dt>
                    </div>
                    <div>
                      <dt class="text-sm font-medium text-gray-500">Email</dt>
                      <dt class="mt-2 text-base font-normal text-gray-900">
                        ricardo.cooper@example.com
                      </dt>
                    </div>
                    <div>
                      <dt class="text-sm font-medium text-gray-500">Phone</dt>
                      <dt class="mt-2 text-base font-normal text-gray-900">
                        +1 (555) 987-6543
                      </dt>
                    </div>
                    <div class="col-span-2">
                      <dt class="text-sm font-medium text-gray-500">
                        Attachments
                      </dt>
                      <dt class="mt-2">
                        <ul class="border border-gray-200 rounded-md">
                          <li class="flex items-center px-4 py-3">
                            <svg
                              class="h-6 w-6 text-gray-400"
                              xmlns="http://www.w3.org/2000/svg"
                              fill="none"
                              viewBox="0 0 24 24"
                              stroke="currentColor"
                            >
                              <path
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                d="M15.172 7l-6.586 6.586a2 2 0 102.828 2.828l6.414-6.586a4 4 0 00-5.656-5.656l-6.415 6.585a6 6 0 108.486 8.486L20.5 13"
                              />
                            </svg>
                            <a href="#" class="ml-3 text-base text-gray-900"
                              >resume_back_end_developer.pdf</a
                            >
                            <a
                              href="#"
                              class="ml-auto text-sm font-medium text-gray-900"
                              >Download</a
                            >
                          </li>
                          <li
                            class="flex items-center px-4 py-3 border-t border-gray-200"
                          >
                            <svg
                              class="h-6 w-6 text-gray-400"
                              xmlns="http://www.w3.org/2000/svg"
                              fill="none"
                              viewBox="0 0 24 24"
                              stroke="currentColor"
                            >
                              <path
                                stroke-linecap="round"
                                stroke-linejoin="round"
                                stroke-width="2"
                                d="M15.172 7l-6.586 6.586a2 2 0 102.828 2.828l6.414-6.586a4 4 0 00-5.656-5.656l-6.415 6.585a6 6 0 108.486 8.486L20.5 13"
                              />
                            </svg>
                            <a href="#" class="ml-3 text-base text-gray-900"
                              >cover_letter_back_end_developer.pdf</a
                            >
                            <a
                              href="#"
                              class="ml-auto text-sm font-medium text-gray-900"
                              >Download</a
                            >
                          </li>
                        </ul>
                      </dt>
                    </div>
                  </dl>
                </div>
                <div>
                  <button
                    class="flex items-center justify-center w-full px-6 py-3 bg-gray-50 space-x-2"
                  >
                    <span class="text-sm font-medium text-gray-500 leading-none"
                      >Read full applicaion</span
                    >
                    <svg
                      class="h-6 w-6 text-gray-400"
                      xmlns="http://www.w3.org/2000/svg"
                      viewBox="0 0 20 20"
                      fill="currentColor"
                    >
                      <path
                        fill-rule="evenodd"
                        d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                        clip-rule="evenodd"
                      />
                    </svg>
                  </button>
                </div>
              </div>
            </div>
            <div></div>
          </div>
          <div class="col-span-1"></div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: 'App',
};
</script>
