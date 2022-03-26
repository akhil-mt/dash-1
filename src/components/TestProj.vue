<script setup></script>

<template>
  <div class="max-h-screen flex">
    <div class="border w-20 p-2 bg-black rounded-lg"></div>
    <div class="border w-full p-2">
      <div class="border p-2 flex">
        <div class="flex flex-col border p-1 h-full w-2/3">
          <div class="border p-1 flex">
            <div class="border w-3/5">
              <div class="text-3xl font-semibold">
                Monitor health of <br />
                your business
              </div>
              <div class="mt-2">
                Control and analyze your data in the easiest way
              </div>
            </div>
            <div class="border w-2/5">
              <div>
                <div class="w-3/5">
                  <div class="flex items-center border-b-2 border-gray-400">
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      class="w-6 h-6 mr-2 text-gray-600"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
                      />
                    </svg>
                    <input
                      type="text"
                      name="name"
                      placeholder="Search"
                      class="w-1/3 py-2 outline-none focus:border-green-400"
                    />
                  </div>
                </div>
                <div class="border-black"></div>
              </div>
              <div>
                <div class="mt-7">
                  <button
                    class="hover:bg-slate-400 text-black py-2 px-4 rounded-full"
                  >
                    Week
                  </button>
                  <button
                    class="hover:bg-slate-400 text-black py-2 px-4 rounded-full ml-16 mr-16"
                  >
                    Month
                  </button>
                  <button
                    class="hover:bg-slate-400 text-black py-2 px-4 rounded-full"
                  >
                    Year
                  </button>
                </div>
              </div>
            </div>
          </div>
          <div class="border flex p-1 justify-between">
            <div
              class="border w-72 rounded-3xl bg-gradient-to-br from-cyan-300 to-pink-400 h-72"
            >
              <div class="flex text-center">
                Views
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-6 w-6"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M20 13V6a2 2 0 00-2-2H6a2 2 0 00-2 2v7m16 0v5a2 2 0 01-2 2H6a2 2 0 01-2-2v-5m16 0h-2.586a1 1 0 00-.707.293l-2.414 2.414a1 1 0 01-.707.293h-3.172a1 1 0 01-.707-.293l-2.414-2.414A1 1 0 006.586 13H4"
                  />
                </svg>
              </div>
              <div></div>
            </div>
            <div class="border w-72 rounded-3xl bg-cyan-300"></div>
            <div class="border w-72 rounded-3xl"></div>
          </div>
        </div>
        <div class="border h-full w-1/3 rounded-3xl"></div>
      </div>
      <div class="border p-2 flex">
        <div class="border h-full w-2/3 p-1">
          <div class="border flex">
            <div class="border w-1/2 text-4xl my-auto">Total profit</div>
            <div class="border w-1/2"></div>
          </div>
          <div class="border h-48 overflow-auto">
            <img
              class="object-contain"
              src="https://i.stack.imgur.com/x17D8.png"
              alt="graph img"
            />
          </div>
        </div>
        <div class="border h-full w-1/3 p-1 flex-col">
          <div class="border flex h-1/5 py-3">
            <button
              class="hover:bg-slate-400 text-black py-2 px-4 rounded-full"
            >
              Objects
            </button>
            <button
              class="hover:bg-slate-400 text-black py-2 px-4 rounded-full"
            >
              Realtors
            </button>
            <div class="my-auto ml-56">
              <button>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-6 w-6"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M8 12h.01M12 12h.01M16 12h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
                  />
                </svg>
              </button>
            </div>
          </div>
          <div class="border flex-col overflow-auto h-44">
            <div
              class="border border-black hover:bg-black hover:text-white rounded-3xl my-1 mx-4 flex justify-center"
            >
              <div></div>
              <div class="my-auto py-8">Windmills Loft</div>
            </div>
            <div
              class="border border-black hover:bg-black hover:text-white rounded-3xl my-1 mx-4 flex justify-center"
            >
              <div></div>
              <div class="my-auto py-8">Seaview Villa</div>
            </div>
            <div
              class="border border-black hover:bg-black hover:text-white rounded-3xl my-1 mx-4 flex justify-center"
            >
              <div></div>
              <div class="my-auto py-8">Family Villa</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
