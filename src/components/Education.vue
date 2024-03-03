<template>
  <div id="edu">
    <div id="education" data-aos="zoom-in" data-aos-duration="800">
      <div class="education-skills">
        <h1>Education and Experience</h1>
      </div>
      <div class="hold-desc">
        <h1>My Journey</h1>
        <hr />
        <div class="desc">
          <div class="para">
            <p>
              I was once a high school student who knew little about IT, but my growing
              interest led me to take a bold step into the IT world after graduation,
              reshaping my career goals.
            </p>
            <p>
              Despite starting college for IT, financial difficulties forced me to leave
              after a year. Undaunted, I took on various jobs, learning valuable skills
              such as teamwork, discipline, and problem-solving.
            </p>
            <p>
              During this journey, I joined Life's Choice Academy, which reignited my
              passion for IT. At the Academy, I gained technical knowledge, personal
              growth, and mentorship, reminding me of the importance of pursuing one's
              passions.
            </p>
            <p>
              Now, I'm fully committed to a rewarding IT career. My journey, filled with
              challenges, has shaped me from a high school novice to a dedicated
              professional. I believe my dedication will not only bring personal happiness
              but also contribute meaningfully to the ever-evolving world of technology.
            </p>
          </div>
          <div class="gif">
            <!-- <img src="../assets/gif/animation_lmhljg2x_small.gif" alt="" /> -->
            <video autoplay loop muted playsinline>
              <source src="../assets/gif/animation_lmhl6skh.mp4" type="video/mp4" />
            </video>
          </div>
        </div>
      </div>
      <div class="education">
        <div class="co">
          <div class="row edu" style="display: flex; justify-content: center">
            <div class="col mt-5 boo" v-for="item in resume" :key="item">
              <div class="card bo">
                <div class="card-body date">
                  <h1>{{ item.year }}</h1>
                  <h2>{{ item.place }}</h2>
                  <p>{{ item.desc }}</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="education-skills">
        <h1>Skills</h1>
      </div>
      <div class="education">
        <div class="co">
          <!-- <div class="row ski" style="display: flex; justify-content: center">
            <div class="col mt-5 skil">
              <div class="card bod">
                <div class="card-body lang">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                    aria-label="PHP"
                    role="img"
                    viewBox="0 0 512 512"
                    fill="#000000"
                  >
                    <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                    <g
                      id="SVGRepo_tracerCarrier"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    ></g>
                    <g id="SVGRepo_iconCarrier">
                      <rect width="512" height="512" rx="15%" fill="#777bb3"></rect>
                      <g stroke="#ffffff" stroke-width="6">
                        <path
                          id="a"
                          d="M155 202H97a3 3 0 0 0-3 2L67 345c0 3 3 3 3 3h30c3 0 3-2 3-2l7-35h27c42 0 63-28 68-53s1-56-50-56zm13 54c-4 19-17 27-35 27h-18l11-53h18c27 0 26 10 24 26z"
                        ></path>
                        <path
                          d="M275 311c-4 0-3-4-3-4l12-61c0-8 6-16-18-15h-18l-15 78s0 3-4 3h-29c-3 0-3-3-3-3l28-141s0-2 4-2h30c3 0 2 3 2 3l-7 34h26c36 0 45 17 42 37l-13 69s0 3-5 3z"
                        ></path>
                        <use xlink:href="#a" x="239"></use>
                      </g>
                    </g>
                  </svg>
                </div>
                <div class="card-body lang">
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                    aria-label="PHP"
                    role="img"
                    viewBox="0 0 512 512"
                    fill="#000000"
                  >
                    <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
                    <g
                      id="SVGRepo_tracerCarrier"
                      stroke-linecap="round"
                      stroke-linejoin="round"
                    ></g>
                    <g id="SVGRepo_iconCarrier">
                      <rect width="512" height="512" rx="15%" fill="#777bb3"></rect>
                      <g stroke="#ffffff" stroke-width="6">
                        <path
                          id="a"
                          d="M155 202H97a3 3 0 0 0-3 2L67 345c0 3 3 3 3 3h30c3 0 3-2 3-2l7-35h27c42 0 63-28 68-53s1-56-50-56zm13 54c-4 19-17 27-35 27h-18l11-53h18c27 0 26 10 24 26z"
                        ></path>
                        <path
                          d="M275 311c-4 0-3-4-3-4l12-61c0-8 6-16-18-15h-18l-15 78s0 3-4 3h-29c-3 0-3-3-3-3l28-141s0-2 4-2h30c3 0 2 3 2 3l-7 34h26c36 0 45 17 42 37l-13 69s0 3-5 3z"
                        ></path>
                        <use xlink:href="#a" x="239"></use>
                      </g>
                    </g>
                  </svg>
                </div>
              </div>
            </div>
          </div> -->
          <div class="skills">
      <div class="skill-content">
        <div class="skill">
          <svg
            viewBox="-52.5 0 361 361"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            preserveAspectRatio="xMidYMid"
            fill="#000000"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <g>
                <path
                  d="M255.554813,70.7657143 L232.31367,331.125451 L127.843868,360.087912 L23.6617143,331.166242 L0.445186813,70.7657143 L255.554813,70.7657143 L255.554813,70.7657143 Z"
                  fill="#E44D26"
                ></path>
                <path
                  d="M128,337.950242 L212.416703,314.546637 L232.277802,92.0573187 L128,92.0573187 L128,337.950242 L128,337.950242 Z"
                  fill="#F16529"
                ></path>
                <path
                  d="M82.8202198,155.932132 L128,155.932132 L128,123.994725 L47.917011,123.994725 L48.6814945,132.562989 L56.530989,220.572835 L128,220.572835 L128,188.636132 L85.7389011,188.636132 L82.8202198,155.932132 L82.8202198,155.932132 Z"
                  fill="#EBEBEB"
                ></path>
                <path
                  d="M90.0177582,236.54189 L57.957978,236.54189 L62.4323516,286.687648 L127.853011,304.848879 L128,304.808088 L128,271.580132 L127.860044,271.617407 L92.2915165,262.013187 L90.0177582,236.54189 L90.0177582,236.54189 Z"
                  fill="#EBEBEB"
                ></path>
                <path
                  d="M24.1807473,0 L40.4107253,0 L40.4107253,16.0351648 L55.2573187,16.0351648 L55.2573187,0 L71.488,0 L71.488,48.5584176 L55.258022,48.5584176 L55.258022,32.2981978 L40.4114286,32.2981978 L40.4114286,48.5584176 L24.1814505,48.5584176 L24.1814505,0 L24.1807473,0 L24.1807473,0 Z"
                  fill="#000000"
                ></path>
                <path
                  d="M92.8309451,16.1026813 L78.5427692,16.1026813 L78.5427692,0 L123.356835,0 L123.356835,16.1026813 L109.06233,16.1026813 L109.06233,48.5584176 L92.8316484,48.5584176 L92.8316484,16.1026813 L92.8309451,16.1026813 L92.8309451,16.1026813 Z"
                  fill="#000000"
                ></path>
                <path
                  d="M130.469275,0 L147.392703,0 L157.802901,17.061978 L168.202549,0 L185.132308,0 L185.132308,48.5584176 L168.969143,48.5584176 L168.969143,24.4901978 L157.802901,41.7554286 L157.523692,41.7554286 L146.349714,24.4901978 L146.349714,48.5584176 L130.469275,48.5584176 L130.469275,0 L130.469275,0 Z"
                  fill="#000000"
                ></path>
                <path
                  d="M193.20967,0 L209.444571,0 L209.444571,32.5077802 L232.268659,32.5077802 L232.268659,48.5584176 L193.20967,48.5584176 L193.20967,0 L193.20967,0 Z"
                  fill="#000000"
                ></path>
                <path
                  d="M127.889582,220.572835 L167.216527,220.572835 L163.509451,261.992791 L127.889582,271.606857 L127.889582,304.833407 L193.362286,286.687648 L193.842637,281.291956 L201.347516,197.212132 L202.126769,188.636132 L127.889582,188.636132 L127.889582,220.572835 L127.889582,220.572835 Z"
                  fill="#FFFFFF"
                ></path>
                <path
                  d="M127.889582,155.854066 L127.889582,155.932132 L205.032791,155.932132 L205.673495,148.753582 L207.128615,132.562989 L207.892396,123.994725 L127.889582,123.994725 L127.889582,155.854066 L127.889582,155.854066 Z"
                  fill="#FFFFFF"
                ></path>
              </g>
            </g>
          </svg>
        </div>
        <div class="skill">
          <svg
            viewBox="-52.5 0 361 361"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            preserveAspectRatio="xMidYMid"
            fill="#000000"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <g>
                <path
                  d="M127.843868,360.087912 L23.6617143,331.166242 L0.445186813,70.7657143 L255.554813,70.7657143 L232.31367,331.125451 L127.843868,360.087912 L127.843868,360.087912 Z"
                  fill="#264DE4"
                ></path>
                <path
                  d="M212.416703,314.546637 L232.277802,92.0573187 L128,92.0573187 L128,337.950242 L212.416703,314.546637 L212.416703,314.546637 Z"
                  fill="#2965F1"
                ></path>
                <path
                  d="M53.6685714,188.636132 L56.530989,220.572835 L128,220.572835 L128,188.636132 L53.6685714,188.636132 L53.6685714,188.636132 Z"
                  fill="#EBEBEB"
                ></path>
                <path
                  d="M47.917011,123.994725 L50.8202198,155.932132 L128,155.932132 L128,123.994725 L47.917011,123.994725 L47.917011,123.994725 Z"
                  fill="#EBEBEB"
                ></path>
                <path
                  d="M128,271.580132 L127.860044,271.617407 L92.2915165,262.013187 L90.0177582,236.54189 L57.957978,236.54189 L62.4323516,286.687648 L127.853011,304.848879 L128,304.808088 L128,271.580132 L128,271.580132 Z"
                  fill="#EBEBEB"
                ></path>
                <path
                  d="M60.4835165,0 L99.1648352,0 L99.1648352,16.1758242 L76.6593407,16.1758242 L76.6593407,32.3516484 L99.1648352,32.3516484 L99.1648352,48.5274725 L60.4835165,48.5274725 L60.4835165,0 L60.4835165,0 Z"
                  fill="#000000"
                ></path>
                <path
                  d="M106.901099,0 L145.582418,0 L145.582418,14.0659341 L123.076923,14.0659341 L123.076923,16.8791209 L145.582418,16.8791209 L145.582418,49.2307692 L106.901099,49.2307692 L106.901099,34.4615385 L129.406593,34.4615385 L129.406593,31.6483516 L106.901099,31.6483516 L106.901099,0 L106.901099,0 Z"
                  fill="#000000"
                ></path>
                <path
                  d="M153.318681,0 L192,0 L192,14.0659341 L169.494505,14.0659341 L169.494505,16.8791209 L192,16.8791209 L192,49.2307692 L153.318681,49.2307692 L153.318681,34.4615385 L175.824176,34.4615385 L175.824176,31.6483516 L153.318681,31.6483516 L153.318681,0 L153.318681,0 Z"
                  fill="#000000"
                ></path>
                <path
                  d="M202.126769,188.636132 L207.892396,123.994725 L127.889582,123.994725 L127.889582,155.932132 L172.892132,155.932132 L169.98611,188.636132 L127.889582,188.636132 L127.889582,220.572835 L167.216527,220.572835 L163.509451,261.992791 L127.889582,271.606857 L127.889582,304.833407 L193.362286,286.687648 L193.842637,281.291956 L201.347516,197.212132 L202.126769,188.636132 L202.126769,188.636132 Z"
                  fill="#FFFFFF"
                ></path>
              </g>
            </g>
          </svg>
        </div>
        <div class="skill">
          <svg
            viewBox="0 0 256 256"
            version="1.1"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            preserveAspectRatio="xMidYMid"
            fill="#000000"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <g>
                <path d="M0,0 L256,0 L256,256 L0,256 L0,0 Z" fill="#F7DF1E"></path>
                <path
                  d="M67.311746,213.932292 L86.902654,202.076241 C90.6821079,208.777346 94.1202286,214.447137 102.367086,214.447137 C110.272203,214.447137 115.256076,211.354819 115.256076,199.326883 L115.256076,117.528787 L139.313575,117.528787 L139.313575,199.666997 C139.313575,224.58433 124.707759,235.925943 103.3984,235.925943 C84.1532952,235.925943 72.9819429,225.958603 67.3113397,213.93026"
                  fill="#000000"
                ></path>
                <path
                  d="M152.380952,211.354413 L171.969422,200.0128 C177.125994,208.433981 183.827911,214.619835 195.684368,214.619835 C205.652521,214.619835 212.009041,209.635962 212.009041,202.762159 C212.009041,194.513676 205.479416,191.592025 194.481168,186.78207 L188.468419,184.202565 C171.111213,176.81473 159.597308,167.53534 159.597308,147.944838 C159.597308,129.901308 173.344508,116.153295 194.825752,116.153295 C210.119924,116.153295 221.117765,121.48094 229.021663,135.400432 L210.29059,147.428775 C206.166146,140.040127 201.699556,137.119289 194.826159,137.119289 C187.78047,137.119289 183.312254,141.587098 183.312254,147.428775 C183.312254,154.646349 187.78047,157.568406 198.089956,162.036622 L204.103924,164.614095 C224.553448,173.378641 236.067352,182.313448 236.067352,202.418387 C236.067352,224.071924 219.055137,235.927975 196.200432,235.927975 C173.860978,235.927975 159.425829,225.274311 152.381359,211.354413"
                  fill="#000000"
                ></path>
              </g>
            </g>
          </svg>
        </div>
        <div class="skill">
          <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <path
                fill-rule="evenodd"
                clip-rule="evenodd"
                d="M4.98488 2C3.61546 2 2.60217 3.19858 2.64753 4.49844C2.69105 5.74725 2.63451 7.36461 2.22732 8.68359C1.81892 10.0064 1.1282 10.8444 0 10.952V12.1666C1.1282 12.2742 1.81892 13.1122 2.22732 14.4351C2.63451 15.754 2.69105 17.3714 2.64753 18.6202C2.60217 19.9199 3.61546 21.1186 4.98508 21.1186H19.0169C20.3864 21.1186 21.3995 19.9201 21.3541 18.6202C21.3106 17.3714 21.3671 15.754 21.7743 14.4351C22.1829 13.1122 22.8718 12.2742 24 12.1666V10.952C22.8718 10.8444 22.1829 10.0064 21.7743 8.68359C21.3671 7.36481 21.3106 5.74725 21.3541 4.49844C21.3995 3.19878 20.3864 2 19.0169 2H4.98468H4.98488ZM16.2712 13.7687C16.2712 15.5586 14.9361 16.6441 12.7206 16.6441H8.94915C8.84127 16.6441 8.7378 16.6012 8.66152 16.5249C8.58523 16.4486 8.54237 16.3452 8.54237 16.2373V6.88136C8.54237 6.77347 8.58523 6.67001 8.66152 6.59372C8.7378 6.51743 8.84127 6.47458 8.94915 6.47458H12.6991C14.5464 6.47458 15.7588 7.47525 15.7588 9.01166C15.7588 10.09 14.9433 11.0555 13.9041 11.2245V11.2809C15.3187 11.4361 16.2712 12.4156 16.2712 13.7687ZM12.3094 7.76407H10.1589V10.8015H11.9701C13.3702 10.8015 14.1423 10.2377 14.1423 9.2299C14.1423 8.28556 13.4784 7.76407 12.3094 7.76407ZM10.1589 12.0068V15.3542H12.3885C13.8462 15.3542 14.6184 14.7692 14.6184 13.6699C14.6184 12.5704 13.8246 12.0066 12.2947 12.0066H10.1589V12.0068Z"
                fill="#ad04fb"
              ></path>
            </g>
          </svg>
        </div>
        <div class="skill">
          <svg
            viewBox="0 -17.5 256 256"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="xMinYMin meet"
            fill="#000000"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <path
                d="M204.8 0H256L128 220.8 0 0h97.92L128 51.2 157.44 0h47.36z"
                fill="#41B883"
              ></path>
              <path
                d="M0 0l128 220.8L256 0h-51.2L128 132.48 50.56 0H0z"
                fill="#41B883"
              ></path>
              <path
                d="M50.56 0L128 133.12 204.8 0h-47.36L128 51.2 97.92 0H50.56z"
                fill="#35495E"
              ></path>
            </g>
          </svg>
        </div>
        <div class="skill">
          <svg
            viewBox="-13 0 282 282"
            xmlns="http://www.w3.org/2000/svg"
            preserveAspectRatio="xMinYMin meet"
            fill="#000000"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <g fill="#8CC84B">
                <path
                  d="M116.504 3.58c6.962-3.985 16.03-4.003 22.986 0 34.995 19.774 70.001 39.517 104.99 59.303 6.581 3.707 10.983 11.031 10.916 18.614v118.968c.049 7.897-4.788 15.396-11.731 19.019-34.88 19.665-69.742 39.354-104.616 59.019-7.106 4.063-16.356 3.75-23.24-.646-10.457-6.062-20.932-12.094-31.39-18.15-2.137-1.274-4.546-2.288-6.055-4.36 1.334-1.798 3.719-2.022 5.657-2.807 4.365-1.388 8.374-3.616 12.384-5.778 1.014-.694 2.252-.428 3.224.193 8.942 5.127 17.805 10.403 26.777 15.481 1.914 1.105 3.852-.362 5.488-1.274 34.228-19.345 68.498-38.617 102.72-57.968 1.268-.61 1.969-1.956 1.866-3.345.024-39.245.006-78.497.012-117.742.145-1.576-.767-3.025-2.192-3.67-34.759-19.575-69.5-39.18-104.253-58.76a3.621 3.621 0 0 0-4.094-.006C91.2 39.257 56.465 58.88 21.712 78.454c-1.42.646-2.373 2.071-2.204 3.653.006 39.245 0 78.497 0 117.748a3.329 3.329 0 0 0 1.89 3.303c9.274 5.259 18.56 10.481 27.84 15.722 5.228 2.814 11.647 4.486 17.407 2.33 5.083-1.823 8.646-7.01 8.549-12.407.048-39.016-.024-78.038.036-117.048-.127-1.732 1.516-3.163 3.2-3 4.456-.03 8.918-.06 13.374.012 1.86-.042 3.14 1.823 2.91 3.568-.018 39.263.048 78.527-.03 117.79.012 10.464-4.287 21.85-13.966 26.97-11.924 6.177-26.662 4.867-38.442-1.056-10.198-5.09-19.93-11.097-29.947-16.55C5.368 215.886.555 208.357.604 200.466V81.497c-.073-7.74 4.504-15.197 11.29-18.85C46.768 42.966 81.636 23.27 116.504 3.58z"
                ></path>
                <path
                  d="M146.928 85.99c15.21-.979 31.493-.58 45.18 6.913 10.597 5.742 16.472 17.793 16.659 29.566-.296 1.588-1.956 2.464-3.472 2.355-4.413-.006-8.827.06-13.24-.03-1.872.072-2.96-1.654-3.195-3.309-1.268-5.633-4.34-11.212-9.642-13.929-8.139-4.075-17.576-3.87-26.451-3.785-6.479.344-13.446.905-18.935 4.715-4.214 2.886-5.494 8.712-3.99 13.404 1.418 3.369 5.307 4.456 8.489 5.458 18.33 4.794 37.754 4.317 55.734 10.626 7.444 2.572 14.726 7.572 17.274 15.366 3.333 10.446 1.872 22.932-5.56 31.318-6.027 6.901-14.805 10.657-23.56 12.697-11.647 2.597-23.734 2.663-35.562 1.51-11.122-1.268-22.696-4.19-31.282-11.768-7.342-6.375-10.928-16.308-10.572-25.895.085-1.619 1.697-2.748 3.248-2.615 4.444-.036 8.888-.048 13.332.006 1.775-.127 3.091 1.407 3.182 3.08.82 5.367 2.837 11 7.517 14.182 9.032 5.827 20.365 5.428 30.707 5.591 8.568-.38 18.186-.495 25.178-6.158 3.689-3.23 4.782-8.634 3.785-13.283-1.08-3.925-5.186-5.754-8.712-6.95-18.095-5.724-37.736-3.647-55.656-10.12-7.275-2.571-14.31-7.432-17.105-14.906-3.9-10.578-2.113-23.662 6.098-31.765 8.006-8.06 19.563-11.164 30.551-12.275z"
                ></path>
              </g>
            </g>
          </svg>
        </div>
        <div class="skill">
          <svg
            viewBox="-18.458 -22.75 191.151 191.151"
            xmlns="http://www.w3.org/2000/svg"
            fill="#000000"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <path d="M-18.458 6.58h191.151v132.49H-18.458V6.58z" fill="none"></path>
              <path
                d="M40.054 113.583h-5.175c-.183-8.735-.687-16.947-1.511-24.642h-.046l-7.879 24.642h-3.94l-7.832-24.642h-.045c-.581 7.388-.947 15.602-1.099 24.642H7.81c.304-10.993 1.068-21.299 2.289-30.919h6.414l7.465 22.719h.046l7.511-22.719h6.137c1.344 11.268 2.138 21.575 2.382 30.919M62.497 90.771c-2.107 11.434-4.887 19.742-8.337 24.928-2.688 3.992-5.633 5.99-8.84 5.99-.855 0-1.91-.258-3.16-.77v-2.757c.611.088 1.328.138 2.152.138 1.498 0 2.702-.412 3.62-1.238 1.098-1.006 1.647-2.137 1.647-3.388 0-.858-.428-2.612-1.282-5.268L42.618 90.77h5.084l4.076 13.19c.916 2.995 1.298 5.086 1.145 6.277 2.229-5.953 3.786-12.444 4.673-19.468h4.901v.002z"
                fill="#5d87a1"
              ></path>
              <path
                d="M131.382 113.583h-14.7V82.664h4.945v27.113h9.755v3.806zM112.834 114.33l-5.684-2.805c.504-.414.986-.862 1.42-1.381 2.416-2.838 3.621-7.035 3.621-12.594 0-10.229-4.014-15.346-12.045-15.346-3.938 0-7.01 1.298-9.207 3.895-2.414 2.84-3.619 7.022-3.619 12.551 0 5.435 1.068 9.422 3.205 11.951 1.955 2.291 4.902 3.438 8.843 3.438 1.47 0 2.819-.18 4.048-.543l7.4 4.308 2.018-3.474zm-18.413-6.934c-1.252-2.014-1.878-5.248-1.878-9.707 0-7.785 2.365-11.682 7.1-11.682 2.475 0 4.289.932 5.449 2.792 1.25 2.017 1.879 5.222 1.879 9.619 0 7.849-2.367 11.774-7.099 11.774-2.476.001-4.29-.928-5.451-2.796M85.165 105.013c0 2.622-.962 4.773-2.884 6.458-1.924 1.678-4.504 2.519-7.737 2.519-3.024 0-5.956-.966-8.794-2.888l1.329-2.655c2.442 1.223 4.653 1.831 6.638 1.831 1.863 0 3.319-.413 4.375-1.232 1.055-.822 1.684-1.975 1.684-3.433 0-1.837-1.281-3.407-3.631-4.722-2.167-1.19-6.501-3.678-6.501-3.678-2.349-1.712-3.525-3.55-3.525-6.578 0-2.506.877-4.529 2.632-6.068 1.757-1.545 4.024-2.315 6.803-2.315 2.87 0 5.479.769 7.829 2.291l-1.192 2.656c-2.01-.854-3.994-1.281-5.951-1.281-1.585 0-2.809.381-3.66 1.146-.858.762-1.387 1.737-1.387 2.933 0 1.828 1.308 3.418 3.722 4.759 2.196 1.192 6.638 3.723 6.638 3.723 2.409 1.709 3.612 3.53 3.612 6.534"
                fill="#f8981d"
              ></path>
              <path
                d="M137.59 72.308c-2.99-.076-5.305.225-7.248 1.047-.561.224-1.453.224-1.531.933.303.3.338.784.601 1.198.448.747 1.229 1.752 1.942 2.276.783.6 1.569 1.194 2.393 1.717 1.453.899 3.1 1.422 4.516 2.318.825.521 1.645 1.195 2.471 1.756.406.299.666.784 1.193.971v-.114c-.264-.336-.339-.822-.598-1.196l-1.122-1.082c-1.084-1.456-2.431-2.727-3.884-3.771-1.196-.824-3.812-1.944-4.297-3.322l-.076-.076c.822-.077 1.797-.375 2.578-.604 1.271-.335 2.43-.259 3.734-.594.6-.15 1.195-.338 1.797-.523v-.337c-.676-.673-1.158-1.567-1.869-2.203-1.902-1.643-3.998-3.25-6.164-4.595-1.16-.749-2.652-1.231-3.887-1.868-.445-.225-1.195-.336-1.457-.71-.67-.822-1.047-1.904-1.533-2.877-1.08-2.053-2.129-4.331-3.061-6.502-.674-1.456-1.084-2.91-1.906-4.257-3.85-6.35-8.031-10.196-14.457-13.971-1.381-.786-3.024-1.121-4.779-1.533l-2.803-.148c-.598-.262-1.197-.973-1.719-1.309-2.132-1.344-7.621-4.257-9.189-.411-1.01 2.431 1.494 4.821 2.354 6.054.635.856 1.458 1.83 1.902 2.802.263.635.337 1.309.6 1.98.598 1.644 1.157 3.473 1.943 5.007.41.782.857 1.604 1.381 2.312.3.414.822.597.936 1.272-.521.744-.562 1.867-.861 2.801-1.344 4.221-.819 9.45 1.086 12.552.596.934 2.018 2.99 3.92 2.202 1.684-.672 1.311-2.801 1.795-4.668.111-.451.038-.747.262-1.043v.073c.521 1.045 1.047 2.052 1.53 3.1 1.159 1.829 3.177 3.735 4.858 5.002.895.676 1.604 1.832 2.725 2.245V74.1h-.074c-.227-.335-.559-.485-.857-.745-.674-.673-1.42-1.495-1.943-2.241-1.566-2.093-2.952-4.41-4.182-6.801-.602-1.16-1.121-2.428-1.606-3.586-.226-.447-.226-1.121-.601-1.346-.562.821-1.381 1.532-1.791 2.538-.711 1.609-.785 3.588-1.049 5.646l-.147.072c-1.19-.299-1.604-1.53-2.056-2.575-1.119-2.654-1.307-6.914-.336-9.976.26-.783 1.385-3.249.936-3.995-.225-.715-.973-1.122-1.383-1.685-.482-.708-1.01-1.604-1.346-2.39-.896-2.091-1.347-4.408-2.312-6.498-.451-.974-1.234-1.982-1.868-2.879-.712-1.008-1.495-1.718-2.058-2.913-.186-.411-.447-1.083-.148-1.53.073-.3.225-.412.523-.487.484-.409 1.867.111 2.352.336 1.385.56 2.543 1.083 3.699 1.867.523.375 1.084 1.085 1.755 1.272h.786c1.193.26 2.538.072 3.661.41 1.979.636 3.772 1.569 5.38 2.576 4.893 3.103 8.928 7.512 11.652 12.778.447.858.637 1.644 1.045 2.539.787 1.832 1.76 3.7 2.541 5.493.785 1.755 1.533 3.547 2.654 5.005.559.784 2.805 1.195 3.812 1.606.745.335 1.905.633 2.577 1.044 1.271.783 2.537 1.682 3.732 2.543.595.448 2.465 1.382 2.576 2.13M99.484 39.844a5.82 5.82 0 0 0-1.529.188v.075h.072c.301.597.824 1.011 1.197 1.532.301.599.562 1.193.857 1.791l.072-.074c.527-.373.789-.971.789-1.868-.227-.264-.262-.522-.451-.784-.22-.374-.705-.56-1.007-.86"
                fill="#5d87a1"
              ></path>
              <path
                d="M141.148 113.578h.774v-3.788h-1.161l-.947 2.585-1.029-2.585h-1.118v3.788h.731v-2.882h.041l1.078 2.882h.557l1.074-2.882v2.882zm-6.235 0h.819v-3.146h1.072v-.643h-3.008v.643h1.115l.002 3.146z"
                fill="#f8981d"
              ></path>
            </g>
          </svg>
        </div>
        <div class="skill">
          <svg
            height="200px"
            width="200px"
            version="1.1"
            id="_x32_"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            viewBox="0 0 512 512"
            xml:space="preserve"
            fill="#000000"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <g>
                <path
                  class="st0"
                  d="M256.004,0C114.8,0.008,0.025,114.801,0,255.996C0.025,397.183,114.8,511.975,256.004,512 C397.191,511.975,511.984,397.183,512,255.996C511.984,114.801,397.191,0.008,256.004,0z M420.735,420.72 c-42.256,42.241-100.456,68.354-164.731,68.362c-64.284-0.008-122.491-26.121-164.732-68.362 c-42.24-42.241-68.345-100.456-68.354-164.724c0.008-64.276,26.114-122.475,68.354-164.731 C133.513,49.04,191.72,22.927,256.004,22.918c64.276,0.008,122.475,26.122,164.731,68.346 c42.224,42.256,68.338,100.447,68.346,164.731C489.073,320.264,462.96,378.479,420.735,420.72z"
                ></path>
                <path
                  class="st0"
                  d="M72.03,173.859h-1.445c-11.141,25.118-17.37,52.885-17.37,82.137c0,79.817,46.109,148.821,113.138,181.918 L72.039,173.859H72.03z"
                ></path>
                <path
                  class="st0"
                  d="M371.166,182.392c-17.484-24.452-14.891-74.438,17.26-79.914c-35.538-30.672-81.8-49.272-132.421-49.272 c-71.894,0-135.006,37.432-171.017,93.857h74.23v26.795h-29.919l69.269,193.887l48.59-129.884l-22.878-64.004h-34.607v-26.795 h124.225v26.795h-32.358l69.855,195.573l35.401-94.572C393.073,249.366,389.404,207.967,371.166,182.392z"
                ></path>
                <path
                  class="st0"
                  d="M444.513,181.277c-0.08,0.77-0.16,1.549-0.273,2.304c-4.905,32.92-35.394,105.127-35.394,105.127 l-44.143,117.996l-9.849,26.346c62.004-34.686,103.939-100.946,103.939-177.054C458.794,229.594,453.696,204.404,444.513,181.277z"
                ></path>
                <path
                  class="st0"
                  d="M211.861,404.962l-16.665,44.537c19.202,6.036,39.616,9.287,60.808,9.287c23.16,0,45.388-3.925,66.122-11.086 l-61.675-172.654L211.861,404.962z"
                ></path>
              </g>
            </g>
          </svg>
        </div>
        <div class="skill">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
            aria-label="PHP"
            role="img"
            viewBox="0 0 512 512"
            fill="#000000"
          >
            <g id="SVGRepo_bgCarrier" stroke-width="0"></g>
            <g
              id="SVGRepo_tracerCarrier"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></g>
            <g id="SVGRepo_iconCarrier">
              <rect width="512" height="512" rx="15%" fill="#777bb3"></rect>
              <g stroke="#ffffff" stroke-width="6">
                <path
                  id="a"
                  d="M155 202H97a3 3 0 0 0-3 2L67 345c0 3 3 3 3 3h30c3 0 3-2 3-2l7-35h27c42 0 63-28 68-53s1-56-50-56zm13 54c-4 19-17 27-35 27h-18l11-53h18c27 0 26 10 24 26z"
                ></path>
                <path
                  d="M275 311c-4 0-3-4-3-4l12-61c0-8 6-16-18-15h-18l-15 78s0 3-4 3h-29c-3 0-3-3-3-3l28-141s0-2 4-2h30c3 0 2 3 2 3l-7 34h26c36 0 45 17 42 37l-13 69s0 3-5 3z"
                ></path>
                <use xlink:href="#a" x="239"></use>
              </g>
            </g>
          </svg>
        </div>
      </div>
    </div>
        </div>
      </div>
    </div>
    <div class="li"></div>
  </div>
</template>

<script>
export default {
  name: "Education",
  data() {
    return {
      resume: [
        {
          year: "2024",
          place: "Moegsign Projects",
          desc: "Currently working in a family owned business.",
        },
        {
          year: "2023",
          place: "Life's Choice Academy",
          desc: "Assigned as a Lecturer Assistant for the new Cohort",
        },
        {
          year: "2022",
          place: "Life's Choice Academy",
          desc:
            "Currently studying IT (Information Technology), at Life's Choice Academy.",
        },
        {
          year: "2021",
          place: "Mr.Price",
          desc:
            "Started working at Mr.Price Retail Store, as a retail sales assistance for 1 year 6 months.",
        },
        {
          year: "2020",
          place: "Leads Capital Group",
          desc:
            "Started working at Leads Capital Group, as a call center agent for 6 months.",
        },
        {
          year: "2020",
          place: "Southern Winds",
          desc:
            "Started working at Southern Winds, a Credit sales company, worked for 1 month.",
        },
        {
          year: "2019",
          place: "Pearson Instituition",
          desc:
            "Studied first year of IT (Information Technology), at Pearsons Instituition.",
        },
        {
          year: "2018",
          place: "Cedar High School",
          desc: "Graduated from Cedar High School of Arts.",
        },
      ],
    };
  },
};
</script>

<style scoped>
.bod {
  width: 17rem;
  height: 14rem;
  text-align: center;
  background-color: wheat;
  border: 2px solid black;
  transition: transform 0.2s;
}

.hold-desc {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.para {
  /* border: 2px solid red; */
  width: 50%;
  /* justify-content: start; */
}

.desc {
  /* border: 2px solid red; */
  width: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding-left: 5rem;
  padding-right: 5rem;
  gap: 3rem;
}

.gif {
  width: 40%;
  height: 25rem;
  /* border: 2px solid black; */
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 50%;
}

.gif video {
  height: 100%;
  border-radius: 50%;
}
.desc p {
  width: 100%;
  height: 100%;
  text-align: start;
  display: flex;
  justify-content: center;
  align-items: center;
  /* border: 2px solid black; */
  /* border-right: 8px solid #66fcf232; */
  /* padding: 5rem; */
}
.bo {
  width: 20rem;
  height: 15rem;
  text-align: center;
  background-color: wheat;
  border: 2px solid black;
  transition: transform 0.2s;
}

.card {
  border-radius: 0;
}

.education-skills {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 5rem;
  margin-bottom: 2rem;
  text-decoration: underline;
}
.skills {
  display: flex;
  justify-content: center;
  align-items: center;
  margin-top: 3rem;
  text-decoration: underline;
}

.card:hover {
  background: white;
  transition: 0.5s;
  box-shadow: 0 20px 30px rgba(0, 0, 0, 0.7);
  transform: scale(1.1);
  overflow: hidden;
}

.li {
  margin-top: 5rem;
  margin-left: 5rem;
  margin-right: 5rem;
  border-bottom: 1px solid black;
}

#education {
  /* margin-left: 5rem;
  margin-right: 5rem; */
  justify-content: center;
  align-items: center;
  display: inline-block;
}

.co {
  display: flex;
  justify-content: center;
  align-items: center;
}

.date {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 5px;
}

.card-body img {
  width: 14rem;
  height: 11rem;
}

.lang {
  display: flex;
  justify-content: center;
  align-items: center;
}

.education {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 2px;
  padding-bottom: 3rem;
}
/* .ski {
  width: 75% !important;
}

.skil {
  display: flex;
  justify-content: center;
  align-items: center;
} */

.boo {
  margin: 1px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.row {
  margin-left: 0;
  margin-right: 0;
  width: 90%;
}

#edu {
  height: 100%;
}

.skills {
  width: 80%;
  height: 100%;
  /* border: 2px solid red; */
}

.skill-content {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  gap: 2rem;
  /* display: grid;
        gap: 20px;
        grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); */
}

.skill {
  width: 200px;
  height: 200px;
  border: 1px solid black;
  background-color: wheat;
  display: flex;
  justify-content: center;
  align-items: center;
}

.skill svg {
  width: 175px;
  height: 175px;
}
.skill:hover {
  background: white;
  transition: 0.5s;
  box-shadow: 0 20px 30px rgba(0, 0, 0, 0.7);
  transform: scale(1.1);
  overflow: hidden;
}

@media screen and (max-width: 650px) {
  #education {
    margin: 0;
  }

  .co {
    display: flex;
    justify-content: center;
  }
  .boo {
    display: flex;
    justify-content: center;
    margin: 0;
  }

  .skil {
    display: flex;
    justify-content: center;
    margin: 0;
  }

  .bo {
    width: 20rem;
  }
  .bod {
    width: 20rem;
  }
  .hold-desc {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .hold-desc h1 {
    text-align: start !important;
    width: 100%;
    padding-left: 1rem;
    text-decoration: underline;
  }

  .para {
    /* border: 2px solid red; */
    width: 100%;
    /* text-align: center; */
    /* justify-content: start; */
  }

  .desc {
    /* border: 2px solid red; */
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding-left: 0;
    padding-right: 0;
  }

  .gif {
    width: 100%;
    height: 15rem;
    /* border: 2px solid black; */
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
  }

  .gif video {
    height: 100%;
    border-radius: 50%;
  }
  .desc p {
    width: 100%;
    height: 100%;
    text-align: start !important;
  }
}

@media screen and (max-width: 1080px) {
  .boo {
    display: flex;
    justify-content: center;
    margin: 0;
  }
  .skil {
    display: flex;
    justify-content: center;
    margin: 0;
  }
  .hold-desc {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
  }

  .para {
    /* border: 2px solid red; */
    width: 100%;
    /* text-align: center; */
    /* justify-content: start; */
  }

  .desc {
    /* border: 2px solid red; */
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    /* padding-left: 5rem;
  padding-right: 5rem; */
  }

  .gif {
    width: 100%;
    height: 15rem;
    /* border: 2px solid black; */
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
  }

  .gif video {
    height: 100%;
    border-radius: 50%;
  }
  .desc p {
    width: 100%;
    height: 100%;
    text-align: center;
    /* display: flex;
  justify-content: center;
  align-items: center; */
    /* border: 2px solid black; */
    /* border-right: 8px solid #66fcf232; */
    /* padding: 5rem; */
  }
}
</style>
