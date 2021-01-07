<template>
  <!-- BEGIN: Weekly Top Products -->
  <div class="col-span-12 mt-6">
    <div class="intro-y block sm:flex items-center h-10">
      <h2 class="text-lg font-medium truncate mr-5">Weekly Top Products</h2>
      <div class="flex items-center sm:ml-auto mt-3 sm:mt-0">
        <button
          class="button box flex items-center text-gray-700 dark:text-gray-300"
        >
          <i data-feather="file-text" class="hidden sm:block w-4 h-4 mr-2"></i>
          Export to Excel
        </button>
        <button
          class="ml-3 button box flex items-center text-gray-700 dark:text-gray-300"
        >
          <i data-feather="file-text" class="hidden sm:block w-4 h-4 mr-2"></i>
          Export to PDF
        </button>
      </div>
    </div>
    <div class="intro-y overflow-auto lg:overflow-visible mt-8 sm:mt-0">
      <table class="table table-report sm:mt-2">
        <thead>
          <tr>
            <th class="whitespace-nowrap">IMAGES</th>
            <th class="whitespace-nowrap">PRODUCT NAME</th>
            <th class="text-center whitespace-nowrap">STOCK</th>
            <th class="text-center whitespace-nowrap">STATUS</th>
            <th class="text-center whitespace-nowrap">ACTIONS</th>
          </tr>
        </thead>
        <tbody>
          <tr class="intro-x">
            <td class="w-40">
              <div class="flex">
                <div class="w-10 h-10 image-fit zoom-in">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-6.jpg"
                    title="Uploaded at 16 May 2020"
                  />
                </div>
                <div class="w-10 h-10 image-fit zoom-in -ml-5">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-5.jpg"
                    title="Uploaded at 8 April 2021"
                  />
                </div>
                <div class="w-10 h-10 image-fit zoom-in -ml-5">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-2.jpg"
                    title="Uploaded at 12 October 2020"
                  />
                </div>
              </div>
            </td>
            <td>
              <a href="" class="font-medium whitespace-nowrap">Nikon Z6</a>
              <div class="text-gray-600 text-xs whitespace-nowrap mt-0.5">
                Photography
              </div>
            </td>
            <td class="text-center">219</td>
            <td class="w-40">
              <div class="flex items-center justify-center text-theme-9">
                <i data-feather="check-square" class="w-4 h-4 mr-2"></i>
                Active
              </div>
            </td>
            <td class="table-report__action w-56">
              <div class="flex justify-center items-center">
                <a class="flex items-center mr-3" href="">
                  <i data-feather="check-square" class="w-4 h-4 mr-1"></i>
                  Edit
                </a>
                <a class="flex items-center text-theme-6" href="">
                  <i data-feather="trash-2" class="w-4 h-4 mr-1"></i>
                  Delete
                </a>
              </div>
            </td>
          </tr>
          <tr class="intro-x">
            <td class="w-40">
              <div class="flex">
                <div class="w-10 h-10 image-fit zoom-in">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-5.jpg"
                    title="Uploaded at 15 July 2022"
                  />
                </div>
                <div class="w-10 h-10 image-fit zoom-in -ml-5">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-11.jpg"
                    title="Uploaded at 23 July 2022"
                  />
                </div>
                <div class="w-10 h-10 image-fit zoom-in -ml-5">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-9.jpg"
                    title="Uploaded at 18 June 2022"
                  />
                </div>
              </div>
            </td>
            <td>
              <a href="" class="font-medium whitespace-nowrap">Sony A7 III</a>
              <div class="text-gray-600 text-xs whitespace-nowrap mt-0.5">
                Photography
              </div>
            </td>
            <td class="text-center">93</td>
            <td class="w-40">
              <div class="flex items-center justify-center text-theme-9">
                <i data-feather="check-square" class="w-4 h-4 mr-2"></i>
                Active
              </div>
            </td>
            <td class="table-report__action w-56">
              <div class="flex justify-center items-center">
                <a class="flex items-center mr-3" href="">
                  <i data-feather="check-square" class="w-4 h-4 mr-1"></i>
                  Edit
                </a>
                <a class="flex items-center text-theme-6" href="">
                  <i data-feather="trash-2" class="w-4 h-4 mr-1"></i>
                  Delete
                </a>
              </div>
            </td>
          </tr>
          <tr class="intro-x">
            <td class="w-40">
              <div class="flex">
                <div class="w-10 h-10 image-fit zoom-in">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-4.jpg"
                    title="Uploaded at 9 July 2020"
                  />
                </div>
                <div class="w-10 h-10 image-fit zoom-in -ml-5">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-11.jpg"
                    title="Uploaded at 19 September 2022"
                  />
                </div>
                <div class="w-10 h-10 image-fit zoom-in -ml-5">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-10.jpg"
                    title="Uploaded at 16 November 2021"
                  />
                </div>
              </div>
            </td>
            <td>
              <a href="" class="font-medium whitespace-nowrap"
                >Sony Master Series A9G</a
              >
              <div class="text-gray-600 text-xs whitespace-nowrap mt-0.5">
                Electronic
              </div>
            </td>
            <td class="text-center">59</td>
            <td class="w-40">
              <div class="flex items-center justify-center text-theme-9">
                <i data-feather="check-square" class="w-4 h-4 mr-2"></i>
                Active
              </div>
            </td>
            <td class="table-report__action w-56">
              <div class="flex justify-center items-center">
                <a class="flex items-center mr-3" href="">
                  <i data-feather="check-square" class="w-4 h-4 mr-1"></i>
                  Edit
                </a>
                <a class="flex items-center text-theme-6" href="">
                  <i data-feather="trash-2" class="w-4 h-4 mr-1"></i>
                  Delete
                </a>
              </div>
            </td>
          </tr>
          <tr class="intro-x">
            <td class="w-40">
              <div class="flex">
                <div class="w-10 h-10 image-fit zoom-in">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-2.jpg"
                    title="Uploaded at 12 February 2022"
                  />
                </div>
                <div class="w-10 h-10 image-fit zoom-in -ml-5">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-4.jpg"
                    title="Uploaded at 12 April 2021"
                  />
                </div>
                <div class="w-10 h-10 image-fit zoom-in -ml-5">
                  <img
                    alt="Midone Tailwind HTML Admin Template"
                    class="tooltip rounded-full"
                    src="/images/preview-12.jpg"
                    title="Uploaded at 1 April 2021"
                  />
                </div>
              </div>
            </td>
            <td>
              <a href="" class="font-medium whitespace-nowrap"
                >Apple MacBook Pro 13</a
              >
              <div class="text-gray-600 text-xs whitespace-nowrap mt-0.5">
                PC &amp; Laptop
              </div>
            </td>
            <td class="text-center">127</td>
            <td class="w-40">
              <div class="flex items-center justify-center text-theme-9">
                <i data-feather="check-square" class="w-4 h-4 mr-2"></i>
                Active
              </div>
            </td>
            <td class="table-report__action w-56">
              <div class="flex justify-center items-center">
                <a class="flex items-center mr-3" href="">
                  <i data-feather="check-square" class="w-4 h-4 mr-1"></i>
                  Edit
                </a>
                <a class="flex items-center text-theme-6" href="">
                  <i data-feather="trash-2" class="w-4 h-4 mr-1"></i>
                  Delete
                </a>
              </div>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
    <div
      class="intro-y flex flex-wrap sm:flex-row sm:flex-nowrap items-center mt-3"
    >
      <ul class="pagination">
        <li>
          <a class="pagination__link" href="">
            <i class="w-4 h-4" data-feather="chevrons-left"></i>
          </a>
        </li>
        <li>
          <a class="pagination__link" href="">
            <i class="w-4 h-4" data-feather="chevron-left"></i>
          </a>
        </li>
        <li><a class="pagination__link" href="">...</a></li>
        <li><a class="pagination__link" href="">1</a></li>
        <li>
          <a class="pagination__link pagination__link--active" href="">2</a>
        </li>
        <li><a class="pagination__link" href="">3</a></li>
        <li><a class="pagination__link" href="">...</a></li>
        <li>
          <a class="pagination__link" href="">
            <i class="w-4 h-4" data-feather="chevron-right"></i>
          </a>
        </li>
        <li>
          <a class="pagination__link" href="">
            <i class="w-4 h-4" data-feather="chevrons-right"></i>
          </a>
        </li>
      </ul>
      <select class="w-20 input box mt-3 sm:mt-0">
        <option>10</option>
        <option>25</option>
        <option>35</option>
        <option>50</option>
      </select>
    </div>
  </div>
  <!-- END: Weekly Top Products -->
</template>
