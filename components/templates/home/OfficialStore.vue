<template>
  <!-- BEGIN: Official Store -->
  <div class="col-span-12 xl:col-span-8 mt-6">
    <div class="intro-y block sm:flex items-center h-10">
      <h2 class="text-lg font-medium truncate mr-5">Official Store</h2>
      <div
        class="sm:ml-auto mt-3 sm:mt-0 relative text-gray-700 dark:text-gray-300"
      >
        <i
          data-feather="map-pin"
          class="w-4 h-4 z-10 absolute my-auto inset-y-0 ml-3 left-0"
        ></i>
        <input
          type="text"
          class="input w-full sm:w-40 box pl-10"
          placeholder="Filter by city"
        />
      </div>
    </div>
    <div class="intro-y box p-5 mt-12 sm:mt-5">
      <div>
        250 Official stores in 21 countries, click the marker to see location
        details.
      </div>
      <div
        class="report-maps mt-5 bg-gray-200 rounded-md"
        data-center="-6.2425342, 106.8626478"
        data-sources="//json/location.json"
      ></div>
    </div>
  </div>
  <!-- END: Official Store -->
</template>
