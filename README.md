<p align="center"><a href="https://github.com/laiguz" target="_blank"><img src="https://avatars.githubusercontent.com/u/138938048?v=4" width="100" alt="Laravel Logo"></a></p>

# Site básico 
## Pacote redes sociais
-Dependencias: 
    >Search Bar personalizado
### V 0.1 
    -Migrate
    -Modal
    -Controller
    -view

### Route
Route::get('/mídias-sociais', SocialMedia::class)->name('social-media');

### SideBar
                        <\a href="{{ route('social-media') }}"
                            class="flex items-center justify-start w-full px-4 py-2 my-1
                            font-thin uppercase transition-colors duration-200
                            {{ Request::is('*mídias*') ? 'bg-gradient-to-r from-white to-blue-100
                            dark:from-gray-700 dark:to-gray-800 text-blue-500 border-r-4 border-blue-500' :
                            'dark:text-gray-200 hover:text-blue-500 text-gray-500' }}" >
                            ><span class="text-left">
                            ><svg class="w-6 h-6" fill="currentColor" viewBox="-1 0 26 26" version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
                                    <title>share</title>
                                    <desc>Created with Sketch Beta.</desc>
                                    <defs>
                                </defs>
                                    <g id="Page-1" stroke="none" stroke-width="1" fill="none" fill-rule="evenodd" sketch:type="MSPage">
                                        <g id="Icon-Set" sketch:type="MSLayerGroup" transform="translate(-312.000000, -726.000000)" fill="currentColor">
                                            <path d="M331,750 C329.343,750 328,748.657 328,747 C328,745.343 329.343,744 331,744 C332.657,744 334,745.343 334,747 C334,748.657 332.657,750 331,750 L331,750 Z M317,742 C315.343,742 314,740.657 314,739 C314,737.344 315.343,736 317,736 C318.657,736 320,737.344 320,739 C320,740.657 318.657,742 317,742 L317,742 Z M331,728 C332.657,728 334,729.343 334,731 C334,732.657 332.657,734 331,734 C329.343,734 328,732.657 328,731 C328,729.343 329.343,728 331,728 L331,728 Z M331,742 C329.23,742 327.685,742.925 326.796,744.312 L321.441,741.252 C321.787,740.572 322,739.814 322,739 C322,738.497 321.903,738.021 321.765,737.563 L327.336,734.38 C328.249,735.37 329.547,736 331,736 C333.762,736 336,733.762 336,731 C336,728.238 333.762,726 331,726 C328.238,726 326,728.238 326,731 C326,731.503 326.097,731.979 326.235,732.438 L320.664,735.62 C319.751,734.631 318.453,734 317,734 C314.238,734 312,736.238 312,739 C312,741.762 314.238,744 317,744 C318.14,744 319.179,743.604 320.02,742.962 L320,743 L326.055,746.46 C326.035,746.64 326,746.814 326,747 C326,749.762 328.238,752 331,752 C333.762,752 336,749.762 336,747 C336,744.238 333.762,742 331,742 L331,742 Z" id="share" sketch:type="MSShapeGroup">
                                </path>
                                        </g>
                                    </g>
                                </svg>
                            </span>
                            ><span class="mx-4 text-sm font-normal">
                                Mídias sociais
                            </span>
                    <\a>
                                
