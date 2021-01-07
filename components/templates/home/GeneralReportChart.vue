<template>
  <!-- BEGIN: General Report -->
  <div class="col-span-12 grid grid-cols-12 gap-6 mt-8">
    <div class="col-span-12 sm:col-span-6 xxl:col-span-3 intro-y">
      <div class="mini-report-chart box p-5 zoom-in">
        <div class="flex items-center">
          <div class="w-2/4 flex-none">
            <div class="text-lg font-medium truncate">Target Sales</div>
            <div class="text-gray-600 mt-1">300 Sales</div>
          </div>
          <div class="flex-none ml-auto relative">
            <canvas id="report-donut-chart-1" width="90" height="90"></canvas>
            <div
              class="font-medium absolute w-full h-full flex items-center justify-center top-0 left-0"
            >
              20%
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col-span-12 sm:col-span-6 xxl:col-span-3 intro-y">
      <div class="mini-report-chart box p-5 zoom-in">
        <div class="flex">
          <div class="text-lg font-medium truncate mr-3">Social Media</div>
          <div
            class="py-1 px-2 rounded-full text-xs bg-gray-200 dark:bg-dark-5 text-gray-600 dark:text-gray-300 cursor-pointer ml-auto truncate"
          >
            320 Followers
          </div>
        </div>
        <div class="mt-4">
          <canvas class="simple-line-chart-1 -ml-1" height="60"></canvas>
        </div>
      </div>
    </div>
    <div class="col-span-12 sm:col-span-6 xxl:col-span-3 intro-y">
      <div class="mini-report-chart box p-5 zoom-in">
        <div class="flex items-center">
          <div class="w-2/4 flex-none">
            <div class="text-lg font-medium truncate">New Products</div>
            <div class="text-gray-600 mt-1">1450 Products</div>
          </div>
          <div class="flex-none ml-auto relative">
            <canvas id="report-donut-chart-2" width="90" height="90"></canvas>
            <div
              class="font-medium absolute w-full h-full flex items-center justify-center top-0 left-0"
            >
              45%
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col-span-12 sm:col-span-6 xxl:col-span-3 intro-y">
      <div class="mini-report-chart box p-5 zoom-in">
        <div class="flex">
          <div class="text-lg font-medium truncate mr-3">Posted Ads</div>
          <div
            class="py-1 px-2 rounded-full text-xs bg-gray-200 dark:bg-dark-5 text-gray-600 dark:text-gray-300 cursor-pointer ml-auto truncate"
          >
            180 Campaign
          </div>
        </div>
        <div class="mt-4">
          <canvas class="simple-line-chart-1 -ml-1" height="60"></canvas>
        </div>
      </div>
    </div>
  </div>
  <!-- END: General Report -->
</template>
