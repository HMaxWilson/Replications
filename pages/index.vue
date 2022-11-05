<template>
  <div class="bg-gray-200 font-source-sans-pro antialiased text-gray-900 leading-normal">
    <div class="flex flex-col items-center min-h-screen border-t-8 border-teal-500 bg-image" style="">
      <div class="mt-24 mb-4">
        <svg class="h-48" viewBox="0 0 90 90" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"><defs><circle id="b" cx="40" cy="40" r="40"/><filter x="-8.8%" y="-6.2%" width="117.5%" height="117.5%" filterUnits="objectBoundingBox" id="a"><feOffset dy="2" in="SourceAlpha" result="shadowOffsetOuter1"/><feGaussianBlur stdDeviation="2" in="shadowOffsetOuter1" result="shadowBlurOuter1"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.1 0" in="shadowBlurOuter1"/></filter><linearGradient x1="0%" y1="0%" y2="100%" id="c"><stop stop-color="#2383AE" offset="0%"/><stop stop-color="#6DD7B9" offset="100%"/></linearGradient></defs><g fill="none" fill-rule="evenodd"><g transform="translate(5 5)"><use fill="#000" filter="url(#a)" xlink:href="#b"/><use fill="#FFF" xlink:href="#b"/></g><path d="M25.6 33.92C27.52 26.24 32.32 22.4 40 22.4c11.52 0 12.96 8.64 18.72 10.08 3.84.96 7.2-.48 10.08-4.32-1.92 7.68-6.72 11.52-14.4 11.52-11.52 0-12.96-8.64-18.72-10.08-3.84-.96-7.2.48-10.08 4.32zM11.2 51.2c1.92-7.68 6.72-11.52 14.4-11.52 11.52 0 12.96 8.64 18.72 10.08 3.84.96 7.2-.48 10.08-4.32-1.92 7.68-6.72 11.52-14.4 11.52-11.52 0-12.96-8.64-18.72-10.08-3.84-.96-7.2.48-10.08 4.32z" fill="url(#c)" transform="translate(5 5)"/></g></svg>
      </div>
      <h1 class="text-3xl font-bold mb-1">Replications</h1>
      <p class="mb-10">Replications of popular webpages using CSS Frameworks.</p>
      <div class="flex flex-wrap items-center justify-between w-3/5 mx-auto mb-10">
        <div class="item-spotify w-64 flex items-center mx-auto mb-8 pr-8">
          <div class="mr-4">
            <p>
              <svg width="80" height="80" viewBox="0 0 80 80" fill="none"><circle cx="40" cy="40" r="40" fill="#fff"/><path d="M39.998 10.1c-16.517 0-29.908 13.39-29.908 29.907 0 16.519 13.391 29.908 29.909 29.908 16.519 0 29.908-13.39 29.908-29.908 0-16.516-13.39-29.906-29.909-29.906V10.1zm13.716 43.135a1.863 1.863 0 01-2.564.618c-7.022-4.29-15.862-5.26-26.273-2.882a1.865 1.865 0 01-.83-3.636c11.393-2.604 21.166-1.482 29.05 3.336a1.864 1.864 0 01.617 2.564zm3.661-8.144a2.331 2.331 0 01-3.207.77c-8.04-4.943-20.294-6.374-29.803-3.488a2.335 2.335 0 01-2.91-1.553 2.335 2.335 0 011.555-2.909c10.862-3.295 24.365-1.699 33.597 3.974a2.33 2.33 0 01.768 3.206zm.314-8.48c-9.639-5.726-25.543-6.252-34.746-3.459a2.797 2.797 0 11-1.624-5.354c10.565-3.207 28.127-2.587 39.225 4.001a2.794 2.794 0 01.979 3.834 2.795 2.795 0 01-3.832.978h-.002z" fill="#1ED760"/></svg>
            </p>
          </div>
          <div class="leading-tight">
            <div>
              <p class="text-lg font-semibold hover:text-gray-600">Spotify</p>
            </div>
            <div>
              <p class="text-xs text-red-400">Coming soon</p>
            </div>
          </div>
        </div>

        <div class="item-discord w-64 flex items-center mx-auto mb-8 pr-8">
          <div class="mr-4">
            <a href="/discord">
              <svg width="80" height="80" fill="none" xmlns="http://www.w3.org/2000/svg"><circle cx="40" cy="40" r="40" fill="#fff" data-darkreader-inline-fill="" style="--darkreader-inline-fill:#181a1b;"></circle>
                <path d="M35.437 37.377c-1.28 0-2.29 1.125-2.29 2.498 0 1.373 1.033 2.498 2.29 2.498 1.28 0 2.29-1.125 2.29-2.498.022-1.373-1.01-2.498-2.29-2.498zm8.194 0c-1.28 0-2.29 1.125-2.29 2.498 0 1.373 1.032 2.498 2.29 2.498 1.28 0 2.29-1.125 2.29-2.498 0-1.373-1.01-2.498-2.29-2.498z" fill="#7289DA" data-darkreader-inline-fill="" style="--darkreader-inline-fill:#74a2da;"></path><path d="M54.54 18.5H24.46c-2.538 0-4.603 2.07-4.603 4.635v30.42c0 2.565 2.066 4.635 4.602 4.635h25.457l-1.19-4.162 2.874 2.677 2.716 2.52 4.827 4.275V23.135c0-2.565-2.065-4.635-4.602-4.635zm-8.664 29.385s-.809-.968-1.482-1.822c2.94-.833 4.063-2.678 4.063-2.678a12.835 12.835 0 0 1-2.581 1.328 14.75 14.75 0 0 1-3.256.967c-2.155.405-4.13.292-5.814-.023a18.812 18.812 0 0 1-3.3-.967 13.141 13.141 0 0 1-1.639-.765c-.067-.045-.134-.067-.202-.112-.045-.023-.067-.046-.09-.068-.404-.225-.628-.383-.628-.383s1.078 1.8 3.929 2.655c-.674.855-1.505 1.868-1.505 1.868-4.96-.157-6.847-3.42-6.847-3.42 0-7.245 3.233-13.118 3.233-13.118 3.233-2.43 6.308-2.362 6.308-2.362l.225.27c-4.041 1.17-5.904 2.948-5.904 2.948s.494-.27 1.324-.653c2.402-1.058 4.31-1.35 5.096-1.418.135-.022.247-.045.382-.045 1.37-.18 2.918-.224 4.534-.044a18.27 18.27 0 0 1 6.758 2.16s-1.774-1.688-5.59-2.858l.314-.36s3.076-.067 6.308 2.363c0 0 3.233 5.872 3.233 13.117 0 0-1.908 3.262-6.87 3.42z" fill="#7289DA" data-darkreader-inline-fill="" style="--darkreader-inline-fill:#21357d;"></path>
              </svg>
            </a>
          </div>
          <div class="leading-tight">
            <div>
              <a href="/discord" class="text-lg font-semibold hover:text-gray-600">Discord</a>
            </div>
            <div>
              <p class="text-xs text-amber-400">In Development</p>
            </div>
          </div>
        </div>

        <div class="item-github w-64 flex items-center mx-auto mb-8 pr-8">
          <div class="mr-4">
            <a href="/github">
              <svg width="80" height="80" viewBox="0 0 80 80" fill="none"><circle cx="40" cy="40" r="40" fill="#fff"/>
                <path d="M40 20c-11.043 0-20 8.955-20 20 0 8.837 5.73 16.333 13.678 18.978.999.185 1.322-.435 1.322-.961v-3.724c-5.563 1.21-6.722-2.36-6.722-2.36-.91-2.311-2.221-2.926-2.221-2.926-1.815-1.242.138-1.215.138-1.215 2.008.14 3.065 2.061 3.065 2.061 1.783 3.057 4.678 2.174 5.82 1.662.178-1.292.697-2.175 1.27-2.673-4.442-.509-9.112-2.224-9.112-9.885 0-2.185.782-3.969 2.06-5.369-.206-.505-.891-2.54.195-5.293 0 0 1.68-.537 5.502 2.05A19.181 19.181 0 0140 29.672c1.7.008 3.412.23 5.01.673 3.818-2.587 5.495-2.05 5.495-2.05 1.088 2.755.403 4.79.197 5.293 1.283 1.4 2.058 3.185 2.058 5.369 0 7.681-4.678 9.373-9.132 9.868.717.62 1.372 1.837 1.372 3.703v5.489c0 .531.32 1.156 1.335.96C54.277 56.328 60 48.833 60 40c0-11.045-8.955-20-20-20z" fill="#161515"/>
              </svg>
            </a>
          </div>
          <div class="leading-tight">
            <div>
              <a href="/github" class="text-lg font-semibold hover:text-gray-600">GitHub</a>
            </div>
            <div>
              <p class="text-xs text-green-400">Complete</p>
            </div>
          </div>
        </div>
      </div>
    </div>

    <a href="https://github.com/hmaxwilson" class="github-corner" aria-label="View source on Github">
      <svg width="80" height="80" viewBox="0 0 250 250" style="fill:#37B2AB; color:#fff; position: absolute; top: 0; border: 0; right: 0;" aria-hidden="true"><path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path><path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path><path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path></svg>
    </a>
  </div>


</template>

<script>
export default {
}
</script>

<style>
.github-corner:hover .octo-arm{animation:octocat-wave 560ms ease-in-out}@keyframes octocat-wave{0%,100%{transform:rotate(0)}20%,60%{transform:rotate(-25deg)}40%,80%{transform:rotate(10deg)}}@media (max-width:500px){.github-corner:hover .octo-arm{animation:none}.github-corner .octo-arm{animation:octocat-wave 560ms ease-in-out}}
</style>
