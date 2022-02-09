<!-- <div class="" markdown="1"></div>
<section class="" markdown="1"></section> -->





<section class="js-fetch-pokemon-hero-section" markdown="1">

<div class="js-fetch-hero-text-holder" markdown="1">

Alex Gardner &#183; Dec 2021

# The Javascript Fetch API Using Pokemon
</div>

<div class="hero-image-holder-quad" markdown="1">

<div class="capture-ball-img-holder pokeball-image-holder">
    <svg width="152" height="285" viewBox="0 0 152 285" fill="none" xmlns="http://www.w3.org/2000/svg">
    <rect width="151.676" height="284.847" transform="matrix(-1 0 0 1 151.866 0)" fill="white"/>
    <mask id="mask0_1167_1686" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="152" height="285">
    <rect width="151.676" height="284.847" transform="matrix(-1 0 0 1 151.866 0)" fill="#C4C4C4"/>
    </mask>
    <g mask="url(#mask0_1167_1686)">
    <circle r="128.049" transform="matrix(-1 0 0 1 0.308228 142.184)" fill="#2C2C2C"/>
    <g filter="url(#filter0_d_1167_1686)">
    <path fill-rule="evenodd" clip-rule="evenodd" d="M36.6917 153.084H127.9C122.368 218.701 67.3562 270.233 0.308137 270.233C-66.7399 270.233 -121.752 218.701 -127.284 153.084H-36.076C-31.3915 168.742 -16.8746 180.155 0.307854 180.155C17.4903 180.155 32.0072 168.742 36.6917 153.084Z" fill="white"/>
    </g>
    <g filter="url(#filter1_d_1167_1686)">
    <circle r="21.2018" transform="matrix(-1 0 0 1 0.308466 142.184)" fill="white"/>
    </g>
    <g filter="url(#filter2_d_1167_1686)">
    <path fill-rule="evenodd" clip-rule="evenodd" d="M36.7632 131.523H127.92C122.502 65.791 67.4378 14.1343 0.308197 14.1343C-66.8214 14.1343 -121.886 65.791 -127.304 131.523H-36.1459C-31.5384 115.741 -16.9613 104.212 0.308609 104.212C17.5785 104.212 32.1556 115.741 36.7632 131.523Z" fill="url(#paint0_linear_1167_1686)"/>
    </g>
    </g>
    <defs>
    <filter id="filter0_d_1167_1686" x="-128.482" y="151.167" width="259.017" height="120.982" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
    <feFlood flood-opacity="0" result="BackgroundImageFix"/>
    <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
    <feOffset dx="0.718704"/>
    <feGaussianBlur stdDeviation="0.958273"/>
    <feComposite in2="hardAlpha" operator="out"/>
    <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
    <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1686"/>
    <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1686" result="shape"/>
    </filter>
    <filter id="filter1_d_1167_1686" x="-22.0914" y="120.982" width="46.2369" height="46.2367" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
    <feFlood flood-opacity="0" result="BackgroundImageFix"/>
    <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
    <feOffset dx="0.718704" dy="1.91655"/>
    <feGaussianBlur stdDeviation="0.958273"/>
    <feComposite in2="hardAlpha" operator="out"/>
    <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
    <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1686"/>
    <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1686" result="shape"/>
    </filter>
    <filter id="filter2_d_1167_1686" x="-128.502" y="14.1343" width="259.057" height="121.221" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
    <feFlood flood-opacity="0" result="BackgroundImageFix"/>
    <feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
    <feOffset dx="0.718704" dy="1.91655"/>
    <feGaussianBlur stdDeviation="0.958273"/>
    <feComposite in2="hardAlpha" operator="out"/>
    <feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
    <feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1686"/>
    <feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1686" result="shape"/>
    </filter>
    <linearGradient id="paint0_linear_1167_1686" x1="11.6877" y1="-22.28" x2="-90.7277" y2="106.368" gradientUnits="userSpaceOnUse">
    <stop stop-color="#C78B97"/>
    <stop offset="0.219943" stop-color="#D11E43"/>
    <stop offset="1" stop-color="#D0002B"/>
    </linearGradient>
    </defs>
    </svg>
</div>


<div class="capture-ball-img-holder great-ball-image-holder">
<svg width="153" height="285" viewBox="0 0 150 285" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="0.627441" width="151.676" height="284.847" fill="white"/>
<mask id="mask0_1167_1703" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="153" height="285">
<rect x="0.627441" width="151.676" height="284.847" fill="#C4C4C4"/>
</mask>
<g mask="url(#mask0_1167_1703)">
<circle cx="152.183" cy="142.184" r="128.049" fill="#2C2C2C"/>
<g filter="url(#filter0_d_1167_1703)">
<path fill-rule="evenodd" clip-rule="evenodd" d="M115.8 153.084H24.5918C30.1233 218.702 85.1355 270.233 152.184 270.233C219.232 270.233 274.244 218.702 279.775 153.084H188.567C183.883 168.743 169.366 180.155 152.183 180.155C135.001 180.155 120.484 168.743 115.8 153.084Z" fill="white"/>
</g>
<g filter="url(#filter1_d_1167_1703)">
<circle cx="152.184" cy="142.184" r="21.2018" fill="white"/>
</g>
<g filter="url(#filter2_d_1167_1703)">
<path fill-rule="evenodd" clip-rule="evenodd" d="M115.729 131.523H24.5713C29.9889 65.7912 85.0534 14.1345 152.183 14.1345C219.313 14.1345 274.377 65.7912 279.795 131.523H188.638C184.03 115.741 169.453 104.212 152.183 104.212C134.913 104.212 120.336 115.741 115.729 131.523Z" fill="url(#paint0_linear_1167_1703)"/>
</g>
<g filter="url(#filter3_d_1167_1703)">
<path fill-rule="evenodd" clip-rule="evenodd" d="M53.6009 60.5912C62.5865 75.9282 72.3432 84.4096 98.6486 107.277C99.08 107.652 99.5158 108.031 99.9562 108.414L116.004 96.5395C88.4783 76.3023 80.3692 62.0163 71.1466 43.1221C64.7516 48.3674 58.8737 54.2198 53.6009 60.5912Z" fill="url(#paint1_linear_1167_1703)"/>
</g>
</g>
<defs>
<filter id="filter0_d_1167_1703" x="23.394" y="151.167" width="259.017" height="120.982" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.718704"/>
<feGaussianBlur stdDeviation="0.958273"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1703"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1703" result="shape"/>
</filter>
<filter id="filter1_d_1167_1703" x="129.784" y="120.982" width="46.2369" height="46.2367" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.718704" dy="1.91655"/>
<feGaussianBlur stdDeviation="0.958273"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1703"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1703" result="shape"/>
</filter>
<filter id="filter2_d_1167_1703" x="23.3734" y="14.1345" width="259.057" height="121.221" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.718704" dy="1.91655"/>
<feGaussianBlur stdDeviation="0.958273"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1703"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1703" result="shape"/>
</filter>
<filter id="filter3_d_1167_1703" x="53.6011" y="42.4034" width="63.3616" height="66.0103" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.958273" dy="-0.718704"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0.691667 0 0 0 0 0.00576389 0 0 0 0 0.153497 0 0 0 1 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1703"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1703" result="shape"/>
</filter>
<linearGradient id="paint0_linear_1167_1703" x1="129.783" y1="-21.681" x2="279.753" y2="131.523" gradientUnits="userSpaceOnUse">
<stop stop-color="#A0C5E8"/>
<stop offset="0.15625" stop-color="#1375D0"/>
<stop offset="1" stop-color="#006BCE"/>
</linearGradient>
<linearGradient id="paint1_linear_1167_1703" x1="111.816" y1="99.301" x2="60.3089" y2="52.4653" gradientUnits="userSpaceOnUse">
<stop stop-color="#C00B2F"/>
<stop offset="0.15625" stop-color="#C00B2F"/>
<stop offset="1" stop-color="#FF6281"/>
</linearGradient>
</defs>
</svg>
</div>


<div class="capture-ball-img-holder ultra-ball-image-holder">
<svg width="152" height="286" viewBox="0 0 152 286" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect width="151.676" height="284.847" transform="matrix(-1 0 0 1 151.866 0.85791)" fill="white"/>
<mask id="mask0_1167_1726" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="152" height="286">
<rect width="151.676" height="284.847" transform="matrix(-1 0 0 1 151.866 0.85791)" fill="#C4C4C4"/>
</mask>
<g mask="url(#mask0_1167_1726)">
<circle r="128.049" transform="matrix(-1 0 0 1 0.450317 143.042)" fill="#2C2C2C"/>
<g filter="url(#filter0_d_1167_1726)">
<path fill-rule="evenodd" clip-rule="evenodd" d="M36.834 153.942H128.042C122.51 219.559 67.4978 271.091 0.449739 271.091C-66.5983 271.091 -121.611 219.559 -127.142 153.942H-35.9336C-31.2492 169.6 -16.7323 181.013 0.450158 181.013C17.6326 181.013 32.1495 169.6 36.834 153.942Z" fill="white"/>
</g>
<g filter="url(#filter1_d_1167_1726)">
<circle r="21.2018" transform="matrix(-1 0 0 1 0.450068 143.042)" fill="white"/>
</g>
<g filter="url(#filter2_d_1167_1726)">
<path fill-rule="evenodd" clip-rule="evenodd" d="M36.9042 132.381H128.061C122.643 66.6491 67.5789 14.9923 0.449304 14.9923C-66.6803 14.9923 -121.745 66.6491 -127.162 132.381H-36.005C-31.3976 116.599 -16.8204 105.07 0.449548 105.07C17.7195 105.07 32.2967 116.599 36.9042 132.381Z" fill="url(#paint0_linear_1167_1726)"/>
</g>
<path fill-rule="evenodd" clip-rule="evenodd" d="M0.321067 14.9924C-30.0698 15.0223 -57.9819 25.6395 -79.9255 43.3545V132.381H-49.2608V37.8711C-9.59827 29.5947 12.2183 29.3135 50.16 37.8711V132.381H80.8247V43.3539C58.8812 25.6393 30.9695 15.0223 0.578941 14.9924H0.321067Z" fill="url(#paint1_linear_1167_1726)"/>
</g>
<defs>
<filter id="filter0_d_1167_1726" x="-128.34" y="152.025" width="259.017" height="120.982" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.718704"/>
<feGaussianBlur stdDeviation="0.958273"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1726"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1726" result="shape"/>
</filter>
<filter id="filter1_d_1167_1726" x="-21.9498" y="121.84" width="46.2369" height="46.2367" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.718704" dy="1.91655"/>
<feGaussianBlur stdDeviation="0.958273"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1726"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1726" result="shape"/>
</filter>
<filter id="filter2_d_1167_1726" x="-128.36" y="14.9923" width="259.057" height="121.222" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.718704" dy="1.91655"/>
<feGaussianBlur stdDeviation="0.958273"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1726"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1726" result="shape"/>
</filter>
<linearGradient id="paint0_linear_1167_1726" x1="92.2044" y1="24.3355" x2="-125.443" y2="123.876" gradientUnits="userSpaceOnUse">
<stop stop-color="#757575"/>
<stop offset="0.197917" stop-color="#323232"/>
<stop offset="1" stop-color="#323232"/>
</linearGradient>
<linearGradient id="paint1_linear_1167_1726" x1="-74.7748" y1="115.611" x2="80.8247" y2="34.9963" gradientUnits="userSpaceOnUse">
<stop stop-color="#FEB63E"/>
<stop offset="0.796875" stop-color="#FEB63E"/>
<stop offset="1" stop-color="#FFEBC9"/>
</linearGradient>
</defs>
</svg>
</div>


<div class="capture-ball-img-holder master-ball-image-holder">
<svg width="153" height="286" viewBox="0 0 150 286" fill="none" xmlns="http://www.w3.org/2000/svg">
<rect x="0.627441" y="0.85791" width="151.676" height="284.847" fill="white"/>
<mask id="mask0_1167_1746" style="mask-type:alpha" maskUnits="userSpaceOnUse" x="0" y="0" width="153" height="286">
<rect x="0.627441" y="0.85791" width="151.676" height="284.847" fill="#C4C4C4"/>
</mask>
<g mask="url(#mask0_1167_1746)">
<circle cx="152.06" cy="143.042" r="128.049" fill="#2C2C2C"/>
<g filter="url(#filter0_d_1167_1746)">
<path fill-rule="evenodd" clip-rule="evenodd" d="M115.676 153.942H24.4683C29.9997 219.559 85.012 271.091 152.06 271.091C219.108 271.091 274.12 219.559 279.652 153.942H188.444C183.759 169.6 169.242 181.013 152.06 181.013C134.877 181.013 120.361 169.6 115.676 153.942Z" fill="white"/>
</g>
<g filter="url(#filter1_d_1167_1746)">
<circle cx="152.06" cy="143.042" r="21.2018" fill="white"/>
</g>
<g filter="url(#filter2_d_1167_1746)">
<path fill-rule="evenodd" clip-rule="evenodd" d="M115.606 132.381H24.4482C29.8659 66.6491 84.9304 14.9924 152.06 14.9924C219.19 14.9924 274.254 66.6491 279.672 132.381H188.516C183.908 116.599 169.331 105.07 152.061 105.07C134.791 105.07 120.214 116.599 115.606 132.381Z" fill="url(#paint0_linear_1167_1746)"/>
</g>
<path d="M117.442 95.7268L136.728 48.5319L151.603 74.8844L166.314 48.5319L186.558 96.4456L173.433 98.8412L165.501 75.8034L151.512 98.1845H151.329L137.467 77.3633L130.23 98.8412L117.442 95.7268Z" fill="white"/>
<g filter="url(#filter3_d_1167_1746)">
<path fill-rule="evenodd" clip-rule="evenodd" d="M39.2007 82.4972C52.864 57.0808 74.8623 36.811 101.538 25.345C111.979 36.8939 111.73 57.9304 100.026 75.6503C86.7548 95.7434 63.7797 103.963 48.7098 94.0097C44.4377 91.188 41.2595 87.2087 39.2007 82.4972Z" fill="url(#paint1_linear_1167_1746)"/>
</g>
</g>
<defs>
<filter id="filter0_d_1167_1746" x="23.2704" y="152.025" width="259.017" height="120.982" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.718704"/>
<feGaussianBlur stdDeviation="0.958273"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1746"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1746" result="shape"/>
</filter>
<filter id="filter1_d_1167_1746" x="129.661" y="121.84" width="46.2369" height="46.2367" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.718704" dy="1.91655"/>
<feGaussianBlur stdDeviation="0.958273"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1746"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1746" result="shape"/>
</filter>
<filter id="filter2_d_1167_1746" x="23.2504" y="14.9924" width="259.057" height="121.221" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="0.718704" dy="1.91655"/>
<feGaussianBlur stdDeviation="0.958273"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.5 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1746"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1746" result="shape"/>
</filter>
<filter id="filter3_d_1167_1746" x="39.2007" y="25.345" width="71.3363" height="74.8095" filterUnits="userSpaceOnUse" color-interpolation-filters="sRGB">
<feFlood flood-opacity="0" result="BackgroundImageFix"/>
<feColorMatrix in="SourceAlpha" type="matrix" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0" result="hardAlpha"/>
<feOffset dx="1.43741" dy="1.91655"/>
<feComposite in2="hardAlpha" operator="out"/>
<feColorMatrix type="matrix" values="0 0 0 0 0.679167 0 0 0 0 0.110365 0 0 0 0 0.597442 0 0 0 1 0"/>
<feBlend mode="normal" in2="BackgroundImageFix" result="effect1_dropShadow_1167_1746"/>
<feBlend mode="normal" in="SourceGraphic" in2="effect1_dropShadow_1167_1746" result="shape"/>
</filter>
<linearGradient id="paint0_linear_1167_1746" x1="279.63" y1="119.684" x2="28.3225" y2="43.1416" gradientUnits="userSpaceOnUse">
<stop stop-color="#602681"/>
<stop offset="0.772904" stop-color="#602681"/>
<stop offset="1" stop-color="#BB8AD7"/>
</linearGradient>
<linearGradient id="paint1_linear_1167_1746" x1="105.225" y1="67.5774" x2="79.5915" y2="54.6407" gradientUnits="userSpaceOnUse">
<stop stop-color="#E83ACF"/>
<stop offset="1" stop-color="#F073DE"/>
</linearGradient>
</defs>
</svg>
</div>

</div>
</section>






<div class="pokemon-fetch__blog-content-holder" markdown="1">

The pokemon API from [pokeAPI](https://pokeapi.co/) provides a fun and intuitive way to access an external API without the need for headers and authentication. More information on additional options for the browser fetch API can be found in the Other Sources section.

<br>

<section class="basic-fetch-example" markdown="1">
<div class="basic-fetch__explanation-and-code" markdown="1">

The simplest type of fetch request takes the path to the resource in question and returns a promise - which resolves into a response object. Within that object, we can call the .json() method to extract the body of the content we fetched (which itself is a promise).

```javascript
// HTTP response object (un-extracted)
fetch("https://pokeapi.co/api/v2/pokemon/magikarp")
.then(res => console.log(res))


// response body (extracted from previous)
fetch("https://pokeapi.co/api/v2/pokemon/magikarp")
.then(res => res.json())
.then(data => console.log(data))
```
</div>

<div class="response-details-holder" markdown="1">
<div class="response-details response-object-details" markdown="1">


Plain Response Object:

```javascript
[object Response] {
  arrayBuffer: function arrayBuffer() {
    [native code]
},
  blob: function blob() {
    [native code]
},
  body: [object ReadableStream] {
    cancel: function cancel() {
      [native code]
},
    getReader: function getReader() {
      [native code]
},
    locked: false,
    tee: function tee() {
      [native code]
}
  },
  bodyUsed: false,
  clone: function clone() {
    [native code]
},
  formData: function formData() {
    [native code]
},
  headers: [object Headers] {
    append: function append() {
      [native code]
},
    delete: function delete() {
      [native code]
},
    entries: function entries() {
      [native code]
},
    forEach: function forEach() {
      [native code]
},
    get: function get() {
      [native code]
},
    has: function has() {
      [native code]
},
    keys: function keys() {
      [native code]
},
    set: function set() {
      [native code]
},
    values: function values() {
      [native code]
}
  },
  json: function json() {
    [native code]
},
  ok: true,
  redirected: false,
  status: 200,
  statusText: "OK",
  text: function text() {
    [native code]
},
  type: "cors",
  url: "https://pokeapi.co/api/v2/pokemon/magikarp"
}
```
</div>
<div class="response-details response-data-unpacked" markdown="1">

Extracted response body: 

```javascript
{
  abilities: [{
  ability: {
    name: "swift-swim",
    url: "https://pokeapi.co/api/v2/ability/33/"
  },
  is_hidden: false,
  slot: 1
}, {
  ability: {
    name: "rattled",
    url: "https://pokeapi.co/api/v2/ability/155/"
  },
  is_hidden: true,
  slot: 3
}],
  base_experience: 40,
  forms: [{
  name: "magikarp",
  url: "https://pokeapi.co/api/v2/pokemon-form/129/"
}],
  game_indices: [{
  game_index: 133,
  version: {
    name: "red",
    url: "https://pokeapi.co/api/v2/version/1/"
  }
}, {
  game_index: 133,
  version: {
    name: "blue",
    url: "https://pokeapi.co/api/v2/version/2/"
  }
}, {
  game_index: 133,
  version: {
    name: "yellow",
    url: "https://pokeapi.co/api/v2/version/3/"
  }
}, {
  game_index: 129,
  version: {
    name: "gold",
    url: "https://pokeapi.co/api/v2/version/4/"
  }
}, {
  game_index: 129,
  version: {
    name: "silver",
    url: "https://pokeapi.co/api/v2/version/5/"
  }
}, {
  game_index: 129,
  version: {
    name: "crystal",
    url: "https://pokeapi.co/api/v2/version/6/"
  }
}, {
  game_index: 129,
  version: {
    name: "ruby",
    url: "https://pokeapi.co/api/v2/version/7/"
  }
}, {
  game_index: 129,
  version: {
    name: "sapphire",
    url: "https://pokeapi.co/api/v2/version/8/"
  }
}, {
  game_index: 129,
  version: {
    name: "emerald",
    url: "https://pokeapi.co/api/v2/version/9/"
  }
}, {
  game_index: 129,
  version: {
    name: "firered",
    url: "https://pokeapi.co/api/v2/version/10/"
  }
}, {
  game_index: 129,
  version: {
    name: "leafgreen",
    url: "https://pokeapi.co/api/v2/version/11/"
  }
}, {
  game_index: 129,
  version: {
    name: "diamond",
    url: "https://pokeapi.co/api/v2/version/12/"
  }
}, {
  game_index: 129,
  version: {
    name: "pearl",
    url: "https://pokeapi.co/api/v2/version/13/"
  }
}, {
  game_index: 129,
  version: {
    name: "platinum",
    url: "https://pokeapi.co/api/v2/version/14/"
  }
}, {
  game_index: 129,
  version: {
    name: "heartgold",
    url: "https://pokeapi.co/api/v2/version/15/"
  }
}, {
  game_index: 129,
  version: {
    name: "soulsilver",
    url: "https://pokeapi.co/api/v2/version/16/"
  }
}, {
  game_index: 129,
  version: {
    name: "black",
    url: "https://pokeapi.co/api/v2/version/17/"
  }
}, {
  game_index: 129,
  version: {
    name: "white",
    url: "https://pokeapi.co/api/v2/version/18/"
  }
}, {
  game_index: 129,
  version: {
    name: "black-2",
    url: "https://pokeapi.co/api/v2/version/21/"
  }
}, {
  game_index: 129,
  version: {
    name: "white-2",
    url: "https://pokeapi.co/api/v2/version/22/"
  }
}],
  height: 9,
  held_items: [],
  id: 129,
  is_default: true,
  location_area_encounters: "https://pokeapi.co/api/v2/pokemon/129/encounters",
  moves: [{
  move: {
    name: "tackle",
    url: "https://pokeapi.co/api/v2/move/33/"
  },
  version_group_details: [{
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "red-blue",
    url: "https://pokeapi.co/api/v2/version-group/1/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "yellow",
    url: "https://pokeapi.co/api/v2/version-group/2/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "gold-silver",
    url: "https://pokeapi.co/api/v2/version-group/3/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "crystal",
    url: "https://pokeapi.co/api/v2/version-group/4/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "ruby-sapphire",
    url: "https://pokeapi.co/api/v2/version-group/5/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "emerald",
    url: "https://pokeapi.co/api/v2/version-group/6/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "firered-leafgreen",
    url: "https://pokeapi.co/api/v2/version-group/7/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "diamond-pearl",
    url: "https://pokeapi.co/api/v2/version-group/8/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "platinum",
    url: "https://pokeapi.co/api/v2/version-group/9/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "heartgold-soulsilver",
    url: "https://pokeapi.co/api/v2/version-group/10/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "black-white",
    url: "https://pokeapi.co/api/v2/version-group/11/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "colosseum",
    url: "https://pokeapi.co/api/v2/version-group/12/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "xd",
    url: "https://pokeapi.co/api/v2/version-group/13/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "black-2-white-2",
    url: "https://pokeapi.co/api/v2/version-group/14/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "x-y",
    url: "https://pokeapi.co/api/v2/version-group/15/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "omega-ruby-alpha-sapphire",
    url: "https://pokeapi.co/api/v2/version-group/16/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "sun-moon",
    url: "https://pokeapi.co/api/v2/version-group/17/"
  }
}, {
  level_learned_at: 15,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "ultra-sun-ultra-moon",
    url: "https://pokeapi.co/api/v2/version-group/18/"
  }
}]
}, {
  move: {
    name: "splash",
    url: "https://pokeapi.co/api/v2/move/150/"
  },
  version_group_details: [{
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "red-blue",
    url: "https://pokeapi.co/api/v2/version-group/1/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "yellow",
    url: "https://pokeapi.co/api/v2/version-group/2/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "gold-silver",
    url: "https://pokeapi.co/api/v2/version-group/3/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "crystal",
    url: "https://pokeapi.co/api/v2/version-group/4/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "ruby-sapphire",
    url: "https://pokeapi.co/api/v2/version-group/5/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "emerald",
    url: "https://pokeapi.co/api/v2/version-group/6/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "firered-leafgreen",
    url: "https://pokeapi.co/api/v2/version-group/7/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "diamond-pearl",
    url: "https://pokeapi.co/api/v2/version-group/8/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "platinum",
    url: "https://pokeapi.co/api/v2/version-group/9/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "heartgold-soulsilver",
    url: "https://pokeapi.co/api/v2/version-group/10/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "black-white",
    url: "https://pokeapi.co/api/v2/version-group/11/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "colosseum",
    url: "https://pokeapi.co/api/v2/version-group/12/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "xd",
    url: "https://pokeapi.co/api/v2/version-group/13/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "black-2-white-2",
    url: "https://pokeapi.co/api/v2/version-group/14/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "x-y",
    url: "https://pokeapi.co/api/v2/version-group/15/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "omega-ruby-alpha-sapphire",
    url: "https://pokeapi.co/api/v2/version-group/16/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "sun-moon",
    url: "https://pokeapi.co/api/v2/version-group/17/"
  }
}, {
  level_learned_at: 1,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "ultra-sun-ultra-moon",
    url: "https://pokeapi.co/api/v2/version-group/18/"
  }
}]
}, {
  move: {
    name: "flail",
    url: "https://pokeapi.co/api/v2/move/175/"
  },
  version_group_details: [{
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "gold-silver",
    url: "https://pokeapi.co/api/v2/version-group/3/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "crystal",
    url: "https://pokeapi.co/api/v2/version-group/4/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "ruby-sapphire",
    url: "https://pokeapi.co/api/v2/version-group/5/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "emerald",
    url: "https://pokeapi.co/api/v2/version-group/6/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "firered-leafgreen",
    url: "https://pokeapi.co/api/v2/version-group/7/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "diamond-pearl",
    url: "https://pokeapi.co/api/v2/version-group/8/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "platinum",
    url: "https://pokeapi.co/api/v2/version-group/9/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "heartgold-soulsilver",
    url: "https://pokeapi.co/api/v2/version-group/10/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "black-white",
    url: "https://pokeapi.co/api/v2/version-group/11/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "colosseum",
    url: "https://pokeapi.co/api/v2/version-group/12/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "xd",
    url: "https://pokeapi.co/api/v2/version-group/13/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "black-2-white-2",
    url: "https://pokeapi.co/api/v2/version-group/14/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "x-y",
    url: "https://pokeapi.co/api/v2/version-group/15/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "omega-ruby-alpha-sapphire",
    url: "https://pokeapi.co/api/v2/version-group/16/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "sun-moon",
    url: "https://pokeapi.co/api/v2/version-group/17/"
  }
}, {
  level_learned_at: 30,
  move_learn_method: {
    name: "level-up",
    url: "https://pokeapi.co/api/v2/move-learn-method/1/"
  },
  version_group: {
    name: "ultra-sun-ultra-moon",
    url: "https://pokeapi.co/api/v2/version-group/18/"
  }
}]
}, {
  move: {
    name: "bounce",
    url: "https://pokeapi.co/api/v2/move/340/"
  },
  version_group_details: [{
  level_learned_at: 0,
  move_learn_method: {
    name: "tutor",
    url: "https://pokeapi.co/api/v2/move-learn-method/3/"
  },
  version_group: {
    name: "platinum",
    url: "https://pokeapi.co/api/v2/version-group/9/"
  }
}, {
  level_learned_at: 0,
  move_learn_method: {
    name: "tutor",
    url: "https://pokeapi.co/api/v2/move-learn-method/3/"
  },
  version_group: {
    name: "heartgold-soulsilver",
    url: "https://pokeapi.co/api/v2/version-group/10/"
  }
}, {
  level_learned_at: 0,
  move_learn_method: {
    name: "tutor",
    url: "https://pokeapi.co/api/v2/move-learn-method/3/"
  },
  version_group: {
    name: "black-2-white-2",
    url: "https://pokeapi.co/api/v2/version-group/14/"
  }
}, {
  level_learned_at: 0,
  move_learn_method: {
    name: "tutor",
    url: "https://pokeapi.co/api/v2/move-learn-method/3/"
  },
  version_group: {
    name: "omega-ruby-alpha-sapphire",
    url: "https://pokeapi.co/api/v2/version-group/16/"
  }
}]
}],
  name: "magikarp",
  order: 199,
  past_types: [],
  species: {
    name: "magikarp",
    url: "https://pokeapi.co/api/v2/pokemon-species/129/"
  },
  sprites: {
    back_default: "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/back/129.png",
    back_female: "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/back/female/129.png",
    back_shiny: "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/back/shiny/129.png",
    back_shiny_female: "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/back/shiny/female/129.png",
    front_default: "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/129.png",
    front_female: "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/female/129.png",
    front_shiny: "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/shiny/129.png",
    front_shiny_female: "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/shiny/female/129.png",
    other: { ... },
    versions: { ... }
  },
  stats: [{
  base_stat: 20,
  effort: 0,
  stat: {
    name: "hp",
    url: "https://pokeapi.co/api/v2/stat/1/"
  }
}, {
  base_stat: 10,
  effort: 0,
  stat: {
    name: "attack",
    url: "https://pokeapi.co/api/v2/stat/2/"
  }
}, {
  base_stat: 55,
  effort: 0,
  stat: {
    name: "defense",
    url: "https://pokeapi.co/api/v2/stat/3/"
  }
}, {
  base_stat: 15,
  effort: 0,
  stat: {
    name: "special-attack",
    url: "https://pokeapi.co/api/v2/stat/4/"
  }
}, {
  base_stat: 20,
  effort: 0,
  stat: {
    name: "special-defense",
    url: "https://pokeapi.co/api/v2/stat/5/"
  }
}, {
  base_stat: 80,
  effort: 1,
  stat: {
    name: "speed",
    url: "https://pokeapi.co/api/v2/stat/6/"
  }
}],
  types: [{
  slot: 1,
  type: {
    name: "water",
    url: "https://pokeapi.co/api/v2/type/11/"
  }
}],
  weight: 100
}
```
</div>
</div>
</section>



<section class="using-fetch-data" markdown="1">
<div class="using-fetch-data__explanation-and-code" markdown="1">

Once the body of the response is retrieved, we can then use the data at will within the body of the promise. Here, we can find URLs to the image of the regular and “shiny” versions of our pokemon.

```javascript
fetch("https://pokeapi.co/api/v2/pokemon/magikarp")
.then(res => res.json())
.then(function(data) {
    console.log(data.sprites.front_default) 
    // "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/129.png"
    console.log(data.sprites.front_shiny) 
    // "https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/shiny/129.png"
})
```
</div>
</section>





<section class="fetch-cascade" markdown="1">
<div class="fetch-cascade__explanation-and-code" markdown="1">

<br>

It is also possible to perform a fetch “cascade” wherein we use information gathered from an initial request to send another request. 

<br>

Here, we use information from our first request to send another  two requests in succession. In this case, we’ve used that data  to generate a list of all pokemon that share magikarp’s first ability. [This Codepen](https://codepen.io/Alx-Gdnr-Pen/pen/MWEEZjz) allows you to edit requests with different options.

<br>

```javascript
const gridHolder = document.querySelector('#pokemon-grid-holder');

// find information on magikarp
fetch("https://pokeapi.co/api/v2/pokemon/magikarp") 
.then(res => res.json())
.then(function(data){

    // destructuring abilities array as received
    [firstAbility, secondAbility, ...rest] = data.abilities 

    // fetching all pokemon who share the first ability
    fetch(`https://pokeapi.co/api/v2/ability/${firstAbility.ability.name}`) 
    .then(abilityRes => abilityRes.json())
    .then(function(abilityData) {
        abilityData.pokemon.forEach(function(pokemonEntry) {

            // fetching the full details of each pokemon gathered
            fetch(`${pokemonEntry.pokemon.url}`)
            .then(res => res.json())
            .then(function(pokemonData) {

                // create DOM nodes to insert the data fetched 
                let gridFigure = document.createElement("div");
                gridFigure.innerHTML = `
                <figure class="pokemon-card">
                <img src="${pokemonData.sprites.other['official-artwork']['front_default']}" alt="Official pokemon artwork of ${pokemonData.name}" class="pokemon-sprite-img">
                <figcaption class="pokemon-card-caption">${pokemonData.name} </figcaption>
                </figure>
                `
                gridHolder.appendChild(gridFigure);
            }
            )
        })
    })
})
```
</div>


</section>
<div class="other-sources">

Other Sources: 

[MDN - Using Promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises)

[MDN - Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch)

[Github - Dan Levy's Examples](https://gist.github.com/justsml/529d0b1ddc5249095ff4b890aad5e801)

[Any API - Documentation For Public APIs](https://any-api.com/)

[Github - Google Chrome POST Sample](https://googlechrome.github.io/samples/fetch-api/fetch-post.html)
</div>

</div>

<!-- <div class="" markdown="1"></div>
<div class="" markdown="1"></div>
<div class="" markdown="1"></div> -->