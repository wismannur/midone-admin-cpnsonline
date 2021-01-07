<template>
  <fragment>
    <client-only>
      <!-- BEGIN: Mobile Menu -->
      <TheMobileMenu />
      <!-- END: Mobile Menu -->
      <div class="flex">
        <!-- BEGIN: Side Menu -->
        <TheSideNav />
        <!-- END: Side Menu -->
        <!-- BEGIN: Content -->
        <div class="content">
          <!-- BEGIN: Top Bar -->
          <div class="top-bar">
            <!-- BEGIN: Breadcrumb -->
            <Breadcrumb />
            <!-- END: Breadcrumb -->
            <!-- BEGIN: Search -->
            <TopSearch />
            <!-- END: Search -->
            <!-- BEGIN: Notifications -->
            <TopNotifications />
            <!-- END: Notifications -->
            <!-- BEGIN: Account Menu -->
            <AccountMenu />
            <!-- END: Account Menu -->
          </div>
          <!-- END: Top Bar -->
          <div class="grid grid-cols-12 gap-6">
            <div class="col-span-12 xxl:col-span-9 grid grid-cols-12 gap-6">
              <!-- BEGIN: General Report -->
              <GeneralReport />
              <!-- END: General Report -->
              <!-- BEGIN: Sales Report -->
              <SalesReport />
              <!-- END: Sales Report -->
              <!-- BEGIN: Weekly Top Seller -->
              <WeeklyTopSeller />
              <!-- END: Weekly Top Seller -->
              <!-- BEGIN: Official Store -->
              <OfficialStore />
              <!-- END: Official Store -->
              <!-- BEGIN: Weekly Best Sellers -->
              <WeeklyBestSellers />
              <!-- END: Weekly Best Sellers -->
              <!-- BEGIN: General Report -->
              <GeneralReportChart />
              <!-- END: General Report -->
              <!-- BEGIN: Weekly Top Products -->
              <WeeklyTopProducts />
              <!-- END: Weekly Top Products -->
            </div>
            <div
              class="col-span-12 xxl:col-span-3 xxl:border-l border-theme-5 -mb-10 pb-10"
            >
              <div class="xxl:pl-6 grid grid-cols-12 gap-6">
                <!-- BEGIN: Transactions -->
                <Transactions />
                <!-- END: Transactions -->
                <!-- BEGIN: Recent Activities -->
                <RecentActivities />
                <!-- END: Recent Activities -->
                <!-- BEGIN: Important Notes -->
                <ImportantNotes />
                <!-- END: Important Notes -->
                <!-- BEGIN: Schedules -->
                <Schedules />
                <!-- END: Schedules -->
              </div>
            </div>
          </div>
        </div>
        <!-- END: Content -->
      </div>
      <!-- BEGIN: JS Assets-->
      <script src="https://developers.google.com/maps/documentation/javascript/examples/markerclusterer/markerclusterer.js"></script>
      <script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAjDvJ3gdZ92nvKNVUGMwCHeaRRU0k92pE&amp;libraries=places"></script>
      <!-- END: JS Assets-->
    </client-only>
  </fragment>
</template>

<script>
export default {
  mounted() {},
  methods: {},
  head() {
    return {}
  },
}
</script>
