<template>
  <div id="mynav">
    <nav>
      <div class="nav-left">Pander</div>
      <div class="nav-right">
        <div v-if="windowWidth > 900">
          <router-link to="/">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  style="vertical-align: middle"
                  t="1624609256530"
                  class="icon"
                  viewBox="0 0 1125 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="3690"
                  width="16"
                  height="16"
                >
                  <path
                    d="M1117.193139 426.43428l-202.62541-154.657998L914.567728 15.911027l-144.745826 0 0 145.355085L558.573136 0 0 426.387414l87.826996 115.103043 60.199454-45.952172 0 528.461693 821.210537 0 0-528.414827 60.129155 45.905306L1117.193139 426.43428zM888.791395 943.577819l-185.425566 0L703.365829 637.987675 413.874176 637.987675l0 305.590144L228.425176 943.577819 228.425176 444.360548l330.171393-252.092537 330.171393 252.092537L888.767962 943.577819z"
                    p-id="3691"
                    fill="#e6e6e6"
                  ></path>
                </svg>
              </a>
              <span>首页</span>
            </div>
          </router-link>
          <router-link to="/music">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957017589"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="3435"
                  width="16"
                  height="16"
                >
                  <path
                    d="M951.1 0L308.4 147.2v127.5h-0.5v481.6c-24.3-17.5-53.9-28.1-86.1-28.1C140.2 728.2 74 794.4 74 876s66.2 147.8 147.8 147.8S369.6 957.7 369.6 876c0-7.5-1.1-14.7-2.2-22h2.2V346.1l519.7-119V648c-24.3-17.5-53.9-28.1-86.1-28.1-81.6 0-147.8 66.2-147.8 147.8s66.2 147.8 147.8 147.8c81.6 0 147.8-66.2 147.8-147.8 0-7.5-1.1-14.7-2.2-22h2.2V0z"
                    fill="#e6e6e6"
                    p-id="3436"
                  ></path>
                </svg>
              </a>
              <span>音乐</span>
            </div>
          </router-link>
          <router-link to="/books">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957135891"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="5247"
                  width="16"
                  height="16"
                >
                  <path
                    d="M77.810668 948.860672c7.153934 5.38873 14.308891 8.942673 23.207561 8.942673 17.886369 1.788739 561.092092 1.788739 566.414307 1.788739l3.576455 0c10.775414 0 17.886369-5.343705 23.252587-14.286378 5.365194-8.942673 7.153934-17.886369 7.153934-26.807552L701.415512 553.978067l0-53.571103 0 0c5.365194 37.516452 12.476149 75.011414 17.842367 112.549356 7.197936 42.88267 14.308891 85.786829 21.463848 128.646985 7.153934 41.09393 14.263865 80.421634 19.631106 121.493052 3.576455 21.441335 7.197936 41.116443 10.731412 62.557778 1.787716 19.652596 12.519128 30.362518 30.361495 33.938973l126.902248 0c7.110955 0 14.308891-1.788739 21.419845-8.942673 5.366218-7.132444 8.942673-14.286378 8.942673-21.440311l0-12.498662c-1.787716-14.287401-1.787716-30.362518-3.576455-44.670385-3.577478-26.786063-7.153934-55.381331-10.68741-82.187861-3.620457-23.229051-7.197936-46.437635-8.986675-71.477938-3.577478-26.78504-7.110955-55.402821-10.68741-82.186837-3.577478-23.230074-7.197936-46.438659-8.986675-71.478961-3.533476-26.806529-7.109931-55.402821-10.68741-82.186837-3.576455-23.229051-7.109931-46.459125-8.942673-71.477938-3.576455-26.806529-7.153934-55.402821-10.68741-82.187861-3.576455-23.229051-7.153934-46.459125-8.942673-71.477938-3.620457-26.806529-7.153934-55.402821-10.731412-82.186837-3.576455-25.01779-7.153934-50.015114-10.68741-75.055416-1.788739-12.498662-5.409197-21.441335-16.096607-30.384008-5.365194-3.554966-10.731412-3.554966-17.886369-5.343705L97.440751 64.408939c-5.322216 1.788739-8.899694 1.788739-14.308891 3.577478C72.444451 75.138304 65.290517 84.059488 65.290517 96.579639l0 829.073472c1.788739 10.709923 3.577478 17.886369 12.520151 23.229051L77.810668 948.860672zM776.448416 103.733573l16.096607 0 12.476149 0c3.577478 0 5.409197 1.76725 5.409197 5.344728 1.788739 17.886369 5.322216 37.516452 7.110955 55.380308 5.365194 41.116443 10.730389 82.20935 16.096607 123.281791 5.365194 41.11542 10.68741 82.20935 16.053628 123.281791 5.409197 41.11542 10.731412 82.20935 16.096607 125.090996 5.322216 41.09393 10.731412 82.187861 16.09763 123.30328 5.321192 41.09393 10.68741 82.166371 16.096607 123.281791 5.321192 41.09393 10.68741 82.20935 16.010649 123.281791 0 5.365194 1.787716 8.942673 1.787716 14.307867 0 1.788739 0 3.577478-3.533476 3.577478l-30.361495 0c-3.577478 0-3.577478-1.788739-3.577478-5.387707-1.788739-17.84339-5.409197-37.516452-7.197936-55.381331-5.322216-41.071418-10.68741-82.186837-16.010649-123.280768-5.409197-41.116443-10.774391-82.187861-16.096607-123.281791-5.365194-41.116443-10.774391-82.187861-16.096607-125.07053-5.365194-41.11542-10.68741-82.20935-16.096607-123.30328-5.366218-41.092907-10.68741-82.186837-16.053628-123.302257-5.409197-41.072441-10.731412-82.166371-16.096607-123.281791 0-5.344728-1.788739-8.942673-1.788739-14.287401C772.870938 103.733573 772.870938 103.733573 776.448416 103.733573L776.448416 103.733573zM701.414489 103.733573l28.573779 0c3.577478 0 5.365194 1.76725 5.365194 5.344728 3.577478 21.441335 5.366218 42.881646 8.942673 62.534242 5.366218 41.09393 10.68741 82.187861 16.053628 123.30328 5.409197 41.09393 10.731412 82.165348 16.096607 123.281791 5.365194 41.09393 10.731412 82.20935 16.096607 123.281791 5.322216 41.092907 10.68741 82.20935 17.886369 125.090996 5.322216 41.072441 10.68741 82.187861 16.053628 123.281791 5.365194 42.88267 12.519128 85.765339 17.842367 128.625496 0 3.598968 0 3.598968-3.533476 3.598968l-16.096607 0-12.476149 0c-3.620457 0-5.409197-1.788739-5.409197-5.365194-5.366218-37.516452-10.68741-76.844156-16.053628-114.360608-5.409197-41.09393-10.731412-82.20935-16.096607-123.281791-5.365194-41.09393-10.731412-82.20935-16.096607-123.281791-5.322216-41.092907-10.68741-82.20935-16.096607-123.30328-5.322216-41.092907-10.68741-82.186837-16.010649-125.069507-5.409197-41.116443-10.774391-82.187861-16.096607-123.281791-3.577478-25.01779-7.153934-51.826366-10.731412-76.844156C697.837011 103.733573 699.62575 103.733573 701.414489 103.733573L701.414489 103.733573zM358.3122 922.075633 233.285672 922.075633 108.172163 922.075633c-3.577478 0-5.322216 0-5.322216-5.365194l0-64.322981c0-3.577478 1.744737-5.366218 5.322216-5.366218l251.971755 0c3.577478 0 5.322216 1.788739 5.322216 5.366218l0 64.322981C363.721397 922.075633 361.889679 922.075633 358.3122 922.075633L358.3122 922.075633zM406.604066 104.715947l248.307296 0c5.409197 0 5.409197 1.787716 5.409197 5.387707l0 402.801972 0 291.233967c0 5.365194-1.788739 7.153934-7.197936 7.153934L404.815327 811.293527c-5.365194 0-5.365194-1.788739-5.365194-5.365194L399.450133 111.848391C399.450133 106.503663 401.238872 104.715947 406.604066 104.715947L406.604066 104.715947zM404.815327 847.02124l125.07053 0 125.026528 0c3.620457 0 5.409197 1.788739 5.409197 5.366218l0 64.322981c0 3.598968-1.788739 5.365194-5.409197 5.365194l-251.927753 0c-3.533476 0-5.322216-1.76725-5.322216-5.365194l0-64.322981C399.450133 848.809979 401.238872 847.02124 404.815327 847.02124L404.815327 847.02124zM108.172163 104.715947l248.394277 0c5.322216 0 5.322216 1.787716 5.322216 5.387707l0 694.03594c0 5.387707-1.74576 5.387707-5.322216 5.387707L108.172163 809.5273c-5.322216 0-5.322216-1.811252-5.322216-5.387707L102.849948 512.905626 102.849948 111.848391C102.849948 106.503663 102.849948 104.715947 108.172163 104.715947L108.172163 104.715947zM108.172163 104.715947"
                    p-id="5248"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M300.466748 208.30114 163.488003 208.30114c-2.704598 0-2.704598 0-2.704598 3.620457l0 28.573779c0 3.577478 1.352811 5.344728 4.100388 5.344728l67.093071 0 68.489884 0c2.704598 0 4.100388 0 4.100388-5.344728l0-28.573779C303.171346 208.30114 303.171346 208.30114 300.466748 208.30114L300.466748 208.30114zM300.466748 208.30114"
                    p-id="5249"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M300.466748 283.356556 163.488003 283.356556c-2.704598 0-2.704598 0-2.704598 3.620457l0 28.573779c0 3.533476 1.352811 5.344728 4.100388 5.344728l67.093071 0 68.489884 0c2.704598 0 4.100388 0 4.100388-5.344728l0-28.573779C303.171346 285.145295 303.171346 283.356556 300.466748 283.356556L300.466748 283.356556zM300.466748 283.356556"
                    p-id="5250"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M300.466748 358.410949 163.488003 358.410949c-2.704598 0-2.704598 0-2.704598 3.576455l0 28.595268c0 3.555989 1.352811 5.344728 4.100388 5.344728l67.093071 0 68.489884 0c2.704598 0 4.100388 0 4.100388-5.344728L304.567135 361.987405C303.171346 360.221178 303.171346 358.410949 300.466748 358.410949L300.466748 358.410949zM300.466748 358.410949"
                    p-id="5251"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M600.730369 208.30114 463.794603 208.30114c-2.792603 0-2.792603 0-2.792603 3.620457l0 28.573779c0 3.577478 1.39579 5.344728 4.14439 5.344728l67.093071 0 68.489884 0c2.705622 0 4.101411 0 4.101411-5.344728l0-28.573779C603.434967 208.30114 603.434967 208.30114 600.730369 208.30114L600.730369 208.30114zM600.730369 208.30114"
                    p-id="5252"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M600.730369 283.356556 463.794603 283.356556c-2.792603 0-2.792603 0-2.792603 3.620457l0 28.573779c0 3.533476 1.39579 5.344728 4.14439 5.344728l67.093071 0 68.489884 0c2.705622 0 4.101411 0 4.101411-5.344728l0-28.573779C603.434967 285.145295 603.434967 283.356556 600.730369 283.356556L600.730369 283.356556zM600.730369 283.356556"
                    p-id="5253"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M600.730369 358.410949 463.794603 358.410949c-2.792603 0-2.792603 0-2.792603 3.576455l0 28.595268c0 3.555989 1.39579 5.344728 4.14439 5.344728l67.093071 0 68.489884 0c2.705622 0 4.101411 0 4.101411-5.344728L604.830757 361.987405C603.434967 360.221178 603.434967 358.410949 600.730369 358.410949L600.730369 358.410949zM600.730369 358.410949"
                    p-id="5254"
                    fill="#e6e6e6"
                  ></path>
                </svg>
              </a>
              <span>书架</span>
            </div>
          </router-link>
          <router-link to="/movie">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957212152"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="6264"
                  width="16"
                  height="16"
                >
                  <path
                    d="M928 960l-832 0C43.072 960 0 916.928 0 864l0-704C0 107.072 43.072 64 96 64l832 0C980.928 64 1024 107.072 1024 160l0 704C1024 916.928 980.928 960 928 960zM96 128C78.336 128 64 142.336 64 160l0 704C64 881.6 78.336 896 96 896l832 0c17.6 0 32-14.4 32-32l0-704C960 142.336 945.6 128 928 128L96 128z"
                    p-id="6265"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M64 320.064l895.872 0 0 64-895.872 0 0-64Z"
                    p-id="6266"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M192 128.064l64 0 0 192-64 0 0-192Z"
                    p-id="6267"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M384 128.064l64 0 0 192-64 0 0-192Z"
                    p-id="6268"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M576 128.064l64 0 0 192-64 0 0-192Z"
                    p-id="6269"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M768 128.064l64 0 0 192-64 0 0-192Z"
                    p-id="6270"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M438.208 519.36C400.32 500.416 384 519.552 384 561.984l0 153.728c0 42.368 16.32 61.504 54.208 42.496l162.88-85.12c37.888-19.008 41.472-49.92 3.712-68.672L438.208 519.36z"
                    p-id="6271"
                    fill="#e6e6e6"
                  ></path>
                </svg>
              </a>
              <span>电影</span>
            </div>
          </router-link>
          <router-link to="/games">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957296108"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="7439"
                  width="16"
                  height="16"
                >
                  <path
                    d="M776 688m-88 0a88 88 0 1 0 176 0 88 88 0 1 0-176 0Z"
                    fill="#e6e6e6"
                    p-id="7440"
                  ></path>
                  <path
                    d="M760 952H264a264 264 0 0 1 0-528h144V267.408l0.232 0.048a87.896 87.896 0 0 1 173.416-15.4A31.84 31.84 0 0 1 584 264v32a24 24 0 0 0 48 0V104a32 32 0 1 1 64 0v196.592l-0.232-0.048a87.896 87.896 0 0 1-173.416 15.4A31.832 31.832 0 0 1 520 304v-32a24 24 0 1 0-48 0v152h288a264 264 0 0 1 0 528z m0-464H264a200 200 0 0 0 0 400h496a200 200 0 1 0 0-400z m-16 288a96 96 0 1 1 96-96 96 96 0 0 1-96 96z m0-128a32 32 0 1 0 32 32 32 32 0 0 0-32-32z m-352 72h-56v56a32 32 0 1 1-64 0v-56h-56a32 32 0 1 1 0-64h56v-56a32 32 0 0 1 64 0v56h56a32 32 0 1 1 0 64z"
                    p-id="7441"
                    fill="#e6e6e6"
                  ></path>
                </svg>
              </a>
              <span>游戏</span>
            </div>
          </router-link>
          <router-link to="/images">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957379646"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="8150"
                  width="16"
                  height="16"
                >
                  <path
                    d="M680.9 468.2c-14.5-25.1-50.7-25.1-65.2 0l-139.2 241c-13.7 23.8-48.1 23.8-61.9 0l-67.8-117.5c-14.5-25.1-50.7-25.1-65.2 0l-98.8 176.6c-6.8 12.1 2 27.1 15.9 27.1h626.8c17.2 0 28.1-18.5 19.7-33.5L680.9 468.2z"
                    fill="#e6e6e6"
                    p-id="8151"
                  ></path>
                  <path
                    d="M825.6 141.2H198.7C124.4 141.2 64 201.7 64 275.9v474.5c0 71.6 56.2 130.2 126.8 134.3 2.6 0.2 5.3 0.4 7.9 0.4h626.8c26.4 0 51-7.7 71.8-20.9 5.5-3.5 10.8-7.4 15.8-11.6 28.8-24.7 47.1-61.3 47.1-102.2V275.9c0.2-74.2-60.3-134.7-134.6-134.7z m80.9 609.3c0 20.8-8 39.8-21 54.1-6.1 6.7-13.4 12.4-21.4 16.8-11.4 6.3-24.5 9.9-38.4 9.9h-627c-11 0-21.5-2.3-31-6.3-8.4-3.5-16.1-8.4-22.8-14.4-16.5-14.8-27-36.2-27-60.1V275.9c0-44.6 36.3-80.8 80.8-80.8h626.9c44.6 0 80.8 36.3 80.8 80.8v474.6z"
                    fill="#e6e6e6"
                    p-id="8152"
                  ></path>
                  <path
                    d="M261.3 335.4m-80.8 0a80.8 80.8 0 1 0 161.6 0 80.8 80.8 0 1 0-161.6 0Z"
                    fill="#e6e6e6"
                    p-id="8153"
                  ></path>
                </svg>
              </a>
              <span>图库</span>
            </div>
          </router-link>
          <router-link to="/labels">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957476654"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="9371"
                  width="16"
                  height="16"
                >
                  <path
                    d="M541.2 632.8c-91.1 0-171.8 41.5-223.3 105.5l231.8 231.8c28.1 28.1 73.8 28.1 101.9 0l155.7-155.7c-37.9-105.6-142.6-181.6-266.1-181.6z"
                    fill="#e6e6e6"
                    p-id="9372"
                  ></path>
                  <path
                    d="M970.2 549.8l-496-496a71.91 71.91 0 0 0-50.9-21.1c-2.4 0-4.9 0.1-7.3 0.4L126.9 62.6C92.9 66 66 92.9 62.6 126.9L33.1 416a71.99 71.99 0 0 0 20.7 58.2l495.9 495.9c14.1 14.1 32.5 21.1 50.9 21.1s36.9-7 50.9-21.1L970 651.6c28.3-28.1 28.3-73.7 0.2-101.8zM600.7 912.5l-491-491 28.8-283 283-28.8 491 491-311.8 311.8z"
                    fill="#e6e6e6"
                    p-id="9373"
                  ></path>
                  <path
                    d="M310.8 210.4c-49.5 0-89.6 40.1-89.6 89.6s40.1 89.6 89.6 89.6 89.6-40.1 89.6-89.6-40.1-89.6-89.6-89.6z m0 102.4c-7.1 0-12.8-5.7-12.8-12.8 0-7.1 5.7-12.8 12.8-12.8 7.1 0 12.8 5.7 12.8 12.8 0 7.1-5.7 12.8-12.8 12.8z"
                    fill="#e6e6e6"
                    p-id="9374"
                  ></path>
                </svg>
              </a>
              <span>标签</span>
            </div>
          </router-link>
          <router-link to="/archive">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957553142"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="10402"
                  width="16"
                  height="16"
                >
                  <path
                    d="M882.9 223.7H571c-6.3 0-12.3-2.3-17-6.4L496.8 167c-11-9.7-25.1-15-39.7-15h-205c-24.2 0.3-43.6 20.1-43.4 44.3v59.2h-65.6c-24.2 0.3-43.6 20.1-43.4 44.3v530.6c-0.2 24.2 19.2 44 43.4 44.3h630.8c24.2-0.3 43.6-20.1 43.4-44.3v-59.2h65.6c24.2-0.3 43.6-20.1 43.4-44.3v-459c0.2-24.2-19.2-44-43.4-44.2zM782.6 830.2c0 4.8-3.8 8.8-8.7 8.9H143.1c-4.8-0.1-8.7-4-8.7-8.9v-364h648.2v364z m0-399.5H134.4V299.6c0-4.8 3.8-8.8 8.7-8.8h205c6.3 0 12.3 2.3 17 6.4l57.2 50.3c11 9.7 25.1 15 39.7 15h311.9c4.8 0.1 8.7 4 8.7 8.9v59.3z m109 296c0 4.8-3.8 8.8-8.7 8.9h-65.6V371.4c0.2-24.2-19.2-44-43.4-44.3H462.1c-6.3 0-12.3-2.3-17-6.4l-57.2-50.3c-11-9.7-25.1-15-39.7-15H243.4v-59.2c0-4.8 3.8-8.8 8.7-8.8h205c6.3 0 12.3 2.3 17 6.4l57.2 50.3c11 9.7 25.1 15 39.7 15h311.9c4.8 0 8.7 4 8.7 8.8v458.8zM713.4 526.5h-104c-9.8 0-17.7 7.9-17.7 17.7s7.9 17.7 17.7 17.7h104c9.8 0 17.7-8 17.6-17.8 0-9.7-7.8-17.6-17.6-17.6z m0 85h-104c-9.8 0.3-17.5 8.5-17.2 18.2 0.3 9.4 7.8 16.9 17.2 17.2h104c9.8-0.3 17.5-8.5 17.2-18.3-0.3-9.3-7.8-16.8-17.2-17.1z"
                    p-id="10403"
                    fill="#e6e6e6"
                  ></path>
                </svg>
              </a>
              <span>归档</span>
            </div>
          </router-link>
          <router-link to="/classify">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957612672"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="11320"
                  width="16"
                  height="16"
                >
                  <path
                    d="M468.8 484.6H276.6c-114.4 0-208.1-93.6-208.1-208.1 0-114.4 93.6-208.1 208.1-208.1 114.4 0 208.1 93.6 208.1 208.1v192.2c-0.1 8.8-7.2 15.9-15.9 15.9zM747.4 484.6H555.2c-8.7 0-15.8-7.1-15.8-15.8V276.6c0-114.4 93.6-208.1 208.1-208.1 114.4 0 208.1 93.6 208.1 208.1-0.1 114.4-93.7 208-208.2 208zM276.6 955.5c-114.4 0-208.1-93.6-208.1-208.1 0-114.4 93.6-208.1 208.1-208.1h192.2c8.7 0 15.8 7.1 15.8 15.8v192.2c0 114.6-93.6 208.2-208 208.2zM747.4 955.5c-114.4 0-208.1-93.6-208.1-208.1V555.2c0-8.7 7.1-15.8 15.8-15.8h192.2c114.4 0 208.1 93.6 208.1 208.1 0.1 114.4-93.5 208-208 208z"
                    p-id="11321"
                    fill="#e6e6e6"
                  ></path>
                </svg>
              </a>
              <span>分类</span>
            </div>
          </router-link>
          <router-link to="/friends">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957665751"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="12303"
                  width="16"
                  height="16"
                >
                  <path
                    d="M262.4 1017.6c-64 0-128-25.6-179.2-76.8-102.4-102.4-102.4-262.4 0-364.8l134.4-134.4 89.6 89.6-134.4 134.4c-51.2 51.2-51.2 128 0 179.2 51.2 51.2 128 51.2 179.2 0l179.2-179.2c25.6-25.6 38.4-57.6 38.4-89.6S556.8 512 537.6 486.4L467.2 422.4l89.6-89.6 70.4 70.4C672 448 697.6 512 697.6 582.4c0 70.4-25.6 134.4-76.8 179.2l-179.2 179.2C396.8 992 326.4 1017.6 262.4 1017.6z"
                    p-id="12304"
                    fill="#e6e6e6"
                  ></path>
                  <path
                    d="M467.2 691.2 396.8 627.2c-102.4-102.4-102.4-262.4 0-364.8l179.2-179.2c102.4-102.4 262.4-102.4 364.8 0 102.4 102.4 102.4 262.4 0 364.8l-134.4 134.4-89.6-89.6 134.4-134.4c51.2-51.2 51.2-128 0-179.2-51.2-51.2-134.4-51.2-179.2 0L486.4 352c-51.2 51.2-51.2 128 0 179.2l70.4 70.4L467.2 691.2z"
                    p-id="12305"
                    fill="#e6e6e6"
                  ></path>
                </svg>
              </a>
              <span>友链</span>
            </div>
          </router-link>
          <router-link to="/leaveinfo">
            <div class="meu_item">
              <a class="nav_home">
                <svg
                  t="1624957774387"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="14812"
                  width="16"
                  height="16"
                >
                  <path
                    d="M853.333333 836.266667c-25.6 0-51.2-6.4-72.533333-21.333334-14.933333-8.533333-19.2-27.733333-10.666667-42.666666s27.733333-19.2 42.666667-10.666667c12.8 8.533333 25.6 10.666667 40.533333 10.666667 46.933333 0 87.466667-44.8 87.466667-98.133334 0-55.466667-38.4-98.133333-87.466667-98.133333-17.066667 0-29.866667-12.8-29.866666-29.866667 0-17.066667 12.8-29.866667 29.866666-29.866666 81.066667 0 149.333333 72.533333 149.333334 160s-66.133333 160-149.333334 160z"
                    fill="#e6e6e6"
                    p-id="14813"
                  ></path>
                  <path
                    d="M868.266667 405.333333c-27.733333-98.133333-369.066667-102.4-409.6-102.4-40.533333 0-401.066667 4.266667-409.6 110.933334-8.533333 36.266667-14.933333 74.666667-14.933334 113.066666 0 206.933333 49.066667 443.733333 424.533334 443.733334 285.866667 0 424.533333-145.066667 424.533333-443.733334 2.133333-40.533333-4.266667-83.2-14.933333-121.6z m-409.6-40.533333c200.533333 0 317.866667 32 343.466666 53.333333-27.733333 21.333333-145.066667 53.333333-343.466666 53.333334S142.933333 437.333333 115.2 418.133333c27.733333-21.333333 145.066667-53.333333 343.466667-53.333333z m2.133333 544c-300.8 0-362.666667-151.466667-362.666667-381.866667 0-17.066667 2.133333-34.133333 4.266667-49.066666 102.4 51.2 326.4 53.333333 358.4 53.333333s258.133333-2.133333 360.533333-53.333333c2.133333 17.066667 4.266667 34.133333 4.266667 51.2-2.133333 262.4-113.066667 379.733333-364.8 379.733333z"
                    fill="#e6e6e6"
                    p-id="14814"
                  ></path>
                  <path
                    d="M347.733333 439.466667c-8.533333 0-17.066667-4.266667-23.466666-10.666667-57.6-66.133333-34.133333-119.466667-14.933334-162.133333 2.133333-6.4 6.4-12.8 8.533334-19.2 8.533333-21.333333-10.666667-83.2-27.733334-119.466667-8.533333-14.933333-2.133333-34.133333 14.933334-40.533333 14.933333-8.533333 34.133333-2.133333 40.533333 14.933333 8.533333 19.2 53.333333 113.066667 29.866667 168.533333-2.133333 6.4-6.4 14.933333-8.533334 21.333334-19.2 40.533333-25.6 59.733333 4.266667 96 10.666667 12.8 10.666667 32-2.133333 42.666666-6.4 6.4-14.933333 8.533333-21.333334 8.533334zM503.466667 439.466667c-8.533333 0-17.066667-4.266667-23.466667-10.666667-57.6-66.133333-34.133333-119.466667-14.933333-162.133333 2.133333-6.4 6.4-12.8 8.533333-19.2 8.533333-21.333333-10.666667-83.2-27.733333-119.466667-8.533333-14.933333-2.133333-34.133333 14.933333-40.533333 14.933333-8.533333 34.133333-2.133333 40.533333 14.933333 8.533333 19.2 53.333333 113.066667 29.866667 168.533333-2.133333 6.4-6.4 14.933333-8.533333 21.333334-19.2 40.533333-25.6 59.733333 4.266666 96 10.666667 12.8 10.666667 32-2.133333 42.666666-8.533333 6.4-14.933333 8.533333-21.333333 8.533334zM659.2 439.466667c-8.533333 0-17.066667-4.266667-23.466667-10.666667-57.6-66.133333-34.133333-119.466667-14.933333-162.133333 2.133333-6.4 6.4-12.8 8.533333-19.2 8.533333-21.333333-10.666667-83.2-27.733333-119.466667-8.533333-14.933333-2.133333-34.133333 14.933333-40.533333 14.933333-8.533333 34.133333-2.133333 40.533334 14.933333 8.533333 19.2 53.333333 113.066667 29.866666 168.533333-2.133333 6.4-6.4 14.933333-8.533333 21.333334-19.2 40.533333-25.6 59.733333 4.266667 96 10.666667 12.8 10.666667 32-2.133334 42.666666-6.4 6.4-12.8 8.533333-21.333333 8.533334z"
                    fill="#e6e6e6"
                    p-id="14815"
                  ></path>
                </svg>
              </a>
              <span>留言</span>
            </div>
          </router-link>
          <router-link to="/about">
            <div class="meu_item">
              <a href="/" class="nav_home">
                <svg
                  t="1624957824724"
                  class="icon"
                  viewBox="0 0 1024 1024"
                  version="1.1"
                  xmlns="http://www.w3.org/2000/svg"
                  p-id="16442"
                  width="16"
                  height="16"
                >
                  <path
                    d="M617.66144 932.60544L301.96736 616.9088l228.62592-228.62336L846.2848 703.97952z"
                    fill="#e6e6e6"
                    p-id="16443"
                  ></path>
                  <path
                    d="M512.2816 933.632L21.9904 443.3408 357.0432 108.288l490.2912 490.2912L512.2816 933.632zM87.1424 443.3408L512.256 868.4544l269.8752-269.9008L357.0432 173.4656 87.1424 443.3408z"
                    fill="#e6e6e6"
                    p-id="16444"
                  ></path>
                  <path
                    d="M512.2816 933.632L177.2032 598.5792 667.4944 108.288l335.0528 335.0528L512.2816 933.632zM242.3808 598.5792l269.9008 269.9008 425.1136-425.1136L667.4944 173.4656 242.3808 598.5792z"
                    fill="#e6e6e6"
                    p-id="16445"
                  ></path>
                </svg>
              </a>
              <span>关于</span>
            </div>
          </router-link>
        </div>
        <div v-else-if="windowWidth < 900">
          <div
            class="gg"
            @click="
              child_home_hide();
              stop();
            "
          >
            <svg
              t="1625837557939"
              class="icon"
              viewBox="0 0 1024 1024"
              version="1.1"
              xmlns="http://www.w3.org/2000/svg"
              p-id="13114"
              width="32"
              height="32"
            >
              <path
                d="M853.333333 213.333333l0 85.333334-682.666666 0L170.666667 213.333333z"
                fill="#e6e6e6"
                p-id="13115"
              ></path>
              <path
                d="M853.333333 469.333333l0 85.333334-682.666666 0L170.666667 469.333333z"
                fill="#e6e6e6"
                p-id="13116"
              ></path>
              <path
                d="M853.333333 725.333333l0 85.333334-682.666666 0L170.666667 725.333333z"
                fill="#e6e6e6"
                p-id="13117"
              ></path>
            </svg>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>
<script>
export default {
  data() {
    return {
      home_hide1: this.home_hide,
      music: "music",
    };
  },
  props: {
    windowWidth: Number,
    home_hide: Boolean,
  },
  methods: {
    // sendmusic:function(val){
    //     this.$emit("listenchangepage",val)
    // },
    //     jumpmusic(){
    // this.$router.push({path:'/music'})
    //     },
    stop: function () {
      var mo = function (e) {
        e.preventDefault();
      };
      document.body.style.overflow = "hidden";
      document.addEventListener("touchmove", mo, false); //禁止页面滑动
    },
    child_home_hide: function () {
      if (this.home_hide1 != " ") {
        this.home_hide1 = true;
        this.$emit("myhide", this.home_hide1);
      } else {
        this.home_hide1 = true;
        this.$emit("myhide", this.home_hide1);
      }
    },
  },
  watch: {},
};
</script>
<style>
.gg {
  height: 40px;
  width: 40px;
}
#mynav {
  position: absolute;
  z-index: 999999;
}
</style>