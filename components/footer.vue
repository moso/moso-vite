<template>
    <footer>
        <ul class="footer-icons">
            <li v-for="(icon, index) in icons" :key="index">
                <!-- eslint-disable-next-line vue/no-v-html -->
                <a :href="icon.url" target="_blank" :title="icon.name" :aria-label="icon.name" rel="noopener" v-html="icon.icon"></a>
            </li>
        </ul>
        <ul class="made-with">
            <li>
                <span>Made with</span>
                <a href="" title="Love" aria-label="Heart">
                    <svg viewBox="0 0 24 24" version="1.1" xmlns="http://www.w3.org/2000/svg">
                        <path fill="red" d="M12.1,18.55L12,18.65L11.89,18.55C7.14,14.24 4,11.39 4,8.5C4,6.5 5.5,5 7.5,5C9.04,5 10.54,6 11.07,7.36H12.93C13.46,6 14.96,5 16.5,5C18.5,5 20,6.5 20,8.5C20,11.39 16.86,14.24 12.1,18.55M16.5,3C14.76,3 13.09,3.81 12,5.08C10.91,3.81 9.24,3 7.5,3C4.42,3 2,5.41 2,8.5C2,12.27 5.4,15.36 10.55,20.03L12,21.35L13.45,20.03C18.6,15.36 22,12.27 22,8.5C22,5.41 19.58,3 16.5,3Z" />
                    </svg>
                </a>
                <span>and</span>
                <a href="https://nuxtjs.org" target="_blank" rel="noopener" title="Nuxt.js" aria-label="Nuxt.js">
                    <svg viewBox="0 0 400 400" version="1.1" xmlns="http://www.w3.org/2000/svg" class="nuxt">
                        <g transform="translate(0 49)" fill="none" fill-rule="evenodd">
                            <path d="M123 292l-1-1c-2-4-2-8-2-12H25L167 27l59 107 19-14-59-107c-1-2-8-13-20-13-5 0-13 2-19 13L4 268c-1 2-7 14-1 24 2 5 8 10 21 10h120c-13 0-19-5-21-10z" fill="#00C58E"/>
                            <path d="M395 269L280 62c-2-2-8-13-20-13-5 0-12 2-19 13l-15 24v48l34-59 114 204h-43a20 20 0 0 1-2 12v1c-6 10-19 10-21 10h68c2 0 15 0 21-10 2-5 4-13-2-23z" fill="#108775"/>
                            <path d="M332 292v-1l1-2c1-3 2-7 1-10l-4-11-90-158-13-24h-1l-13 24-91 158-3 11a21 21 0 0 0 2 13c3 5 9 10 21 10h168c3 0 16 0 22-10zM226 134l83 145H144l82-145z" fill="#2F495E" fill-rule="nonzero"/>
                        </g>
                    </svg>
                </a>
                <span>+</span>
                <a class="vite" href="https://vitejs.dev" target="_blank" rel="noopener" title="Vite" aria-label="Vite">
                    <svg viewBox="0 0 410 404" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path d="M399.641 59.5246L215.643 388.545C211.844 395.338 202.084 395.378 198.228 388.618L10.5817 59.5563C6.38087 52.1896 12.6802 43.2665 21.0281 44.7586L205.223 77.6824C206.398 77.8924 207.601 77.8904 208.776 77.6763L389.119 44.8058C397.439 43.2894 403.768 52.1434 399.641 59.5246Z" fill="url(#paint0_linear)"/>
                        <path d="M292.965 1.5744L156.801 28.2552C154.563 28.6937 152.906 30.5903 152.771 32.8664L144.395 174.33C144.198 177.662 147.258 180.248 150.51 179.498L188.42 170.749C191.967 169.931 195.172 173.055 194.443 176.622L183.18 231.775C182.422 235.487 185.907 238.661 189.532 237.56L212.947 230.446C216.577 229.344 220.065 232.527 219.297 236.242L201.398 322.875C200.278 328.294 207.486 331.249 210.492 326.603L212.5 323.5L323.454 102.072C325.312 98.3645 322.108 94.137 318.036 94.9228L279.014 102.454C275.347 103.161 272.227 99.746 273.262 96.1583L298.731 7.86689C299.767 4.27314 296.636 0.855181 292.965 1.5744Z" fill="url(#paint1_linear)"/>
                        <defs>
                            <linearGradient id="paint0_linear" x1="6.00017" y1="32.9999" x2="235" y2="344" gradientUnits="userSpaceOnUse">
                                <stop stop-color="#41D1FF"/>
                                <stop offset="1" stop-color="#BD34FE"/>
                            </linearGradient>
                            <linearGradient id="paint1_linear" x1="194.651" y1="8.81818" x2="236.076" y2="292.989" gradientUnits="userSpaceOnUse">
                                <stop stop-color="#FFEA83"/>
                                <stop offset="0.0833333" stop-color="#FFDD35"/>
                                <stop offset="1" stop-color="#FFA800"/>
                            </linearGradient>
                        </defs>
                    </svg>
                </a>
                .
                <a href="/info" title="Info" arial-label="Info">
                    <svg viewBox="0 0 20 20" version="1.1" xmlns="http://www.w3.org/2000/svg" class="info">
                        <path d="M12,2A10,10,0,1,0,22,12,10,10,0,0,0,12,2Zm0,5a1.5,1.5,0,1,1-1.5,1.5A1.5,1.5,0,0,1,12,7Zm1.5,10h-3a.5.5,0,1,1,0-1H11V12h-.51a.5.5,0,1,1,0-1h2a.5.5,0,0,1,.5.5V16h.51a.5.5,0,1,1,0,1Z" transform="translate(-2 -2)"/>
                    </svg>
                </a>
            </li>
        </ul>
    </footer>
</template>

<script>
export default {
    data() {
        return {
            icons: [
                {
                    'name': 'GitHub',
                    'url': 'https://github.com/moso',
                    'icon': '<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 24 24" class="github"><path d="m12 2a10 10 0 0 0 -10 10c0 4.42 2.87 8.17 6.84 9.5 0.5 0.08 0.66-0.23 0.66-0.5v-1.69c-2.77 0.6-3.36-1.34-3.36-1.34-0.46-1.16-1.11-1.47-1.11-1.47-0.91-0.62 0.07-0.6 0.07-0.6 1 0.07 1.53 1.03 1.53 1.03 0.87 1.52 2.34 1.07 2.91 0.83 0.09-0.65 0.35-1.09 0.63-1.34-2.22-0.25-4.55-1.11-4.55-4.92 0-1.11 0.38-2 1.03-2.71-0.1-0.25-0.45-1.29 0.1-2.64 0 0 0.84-0.27 2.75 1.02 0.79-0.22 1.65-0.33 2.5-0.33s1.71 0.11 2.5 0.33c1.91-1.29 2.75-1.02 2.75-1.02 0.55 1.35 0.2 2.39 0.1 2.64 0.65 0.71 1.03 1.6 1.03 2.71 0 3.82-2.34 4.66-4.57 4.91 0.36 0.31 0.69 0.92 0.69 1.85v2.74c0 0.27 0.16 0.59 0.67 0.5 3.97-1.34 6.83-5.08 6.83-9.5a10 10 0 0 0 -10 -10z"/></svg>'
                },
                {
                    'name': 'CodePen',
                    'url': 'https://codepen.io/moso',
                    'icon': '<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 24 24" class="codepen"><path d="m19.45 13.29l-1.95-1.29 1.95-1.29m-6.68 8.07v-3.61l3.36-2.24 2.7 1.81m-6.83-0.91l-2.74-1.83 2.74-1.83 2.74 1.83m-3.51 6.78l-6.06-4.04 2.7-1.81 3.36 2.24m-6.68-4.46l1.95 1.29-1.95 1.29m6.68-8.07v3.61l-3.36 2.24-2.7-1.81m7.6-4.04l6.06 4.04-2.7 1.81-3.36-2.24m8.23 0.33v-0.04c0-0.02 0-0.04-0.03-0.06 0-0.01 0-0.03-0.01-0.06 0 0-0.01 0-0.02-0.04 0-0.01-0.01-0.02-0.02-0.03 0-0.02-0.01-0.04-0.02-0.05-0.01-0.02-0.02-0.03-0.02-0.04-0.01-0.02-0.03-0.03-0.04-0.05-0.01-0.01-0.01-0.02-0.02-0.03a0.04 0.04 0 0 0 -0.04 -0.04l-0.03-0.03c-0.02-0.02-0.03-0.03-0.05-0.04l-0.03-0.03c-0.01 0-0.01 0-0.01-0.01l-8.23-5.48c-0.26-0.17-0.6-0.17-0.86 0l-8.23 5.48c0 0.01 0 0.01-0.01 0.01l-0.03 0.03c-0.02 0.01-0.03 0.02-0.05 0.04l-0.03 0.03-0.04 0.04c-0.01 0.01-0.01 0.02-0.02 0.03-0.01 0.02-0.03 0.03-0.04 0.05 0 0.01-0.01 0.02-0.02 0.04-0.01 0.01-0.02 0.03-0.02 0.05-0.01 0.01-0.02 0.02-0.02 0.03-0.01 0.04-0.01 0.04-0.02 0.04-0.01 0.03-0.01 0.05-0.01 0.06-0.03 0.02-0.03 0.04-0.03 0.06v0.04 0.1 5.48 0.1 0.04c0 0.02 0 0.04 0.03 0.06 0 0.01 0 0.03 0.01 0.06 0.01 0 0.01 0 0.02 0.04 0 0.01 0.01 0.02 0.02 0.03 0 0.02 0.01 0.04 0.02 0.05 0.01 0.02 0.02 0.03 0.02 0.04 0.01 0.02 0.03 0.03 0.04 0.05 0.01 0.01 0.01 0.02 0.02 0.03 0.02 0.01 0.03 0.03 0.04 0.04l0.03 0.03c0.02 0.02 0.03 0.03 0.05 0.04l0.03 0.03c0.01 0 0.01 0 0.01 0.01l8.23 5.48c0.13 0.09 0.28 0.13 0.43 0.13s0.3-0.04 0.43-0.13l8.23-5.48c0-0.01 0-0.01 0.01-0.01l0.03-0.03c0.02-0.01 0.03-0.02 0.05-0.04l0.03-0.03c0.01-0.01 0.02-0.03 0.04-0.04 0.01-0.01 0.01-0.02 0.02-0.03 0.01-0.02 0.03-0.03 0.04-0.05 0-0.01 0.01-0.02 0.02-0.04 0.01-0.01 0.02-0.03 0.02-0.05 0.01-0.01 0.02-0.02 0.02-0.03 0.01-0.04 0.02-0.04 0.02-0.04 0.01-0.03 0.01-0.05 0.01-0.06 0.03-0.02 0.03-0.04 0.03-0.06v-0.04-0.1-5.48-0.1z"/></svg>'
                },
                {
                    'name': 'Twitter',
                    'url': 'https://twitter.com/@mosolicious',
                    'icon': '<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 24 24"><path fill="#1da1f2" d="m22.46 6c-0.77 0.35-1.6 0.58-2.46 0.69 0.88-0.53 1.56-1.37 1.88-2.38-0.83 0.5-1.75 0.85-2.72 1.05-0.79-0.86-1.9-1.36-3.16-1.36-2.35 0-4.27 1.92-4.27 4.29 0 0.34 0.04 0.67 0.11 0.98-3.56-0.18-6.73-1.89-8.84-4.48-0.37 0.63-0.58 1.37-0.58 2.15 0 1.49 0.75 2.81 1.91 3.56-0.71 0-1.37-0.2-1.95-0.5v0.03c0 2.08 1.48 3.82 3.44 4.21-0.36 0.1-0.74 0.15-1.13 0.15-0.27 0-0.54-0.03-0.8-0.08 0.54 1.69 2.11 2.95 4 2.98-1.46 1.16-3.31 1.84-5.33 1.84-0.34 0-0.68-0.02-1.02-0.06 1.9 1.22 4.16 1.93 6.58 1.93 7.88 0 12.21-6.54 12.21-12.21 0-0.19 0-0.37-0.01-0.56 0.84-0.6 1.56-1.36 2.14-2.23z"/></svg>'
                },
                {
                    'name': 'LinkedIn',
                    'url': 'https://linkedin.com/in/moso',
                    'icon': '<svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 24 24"><path fill="#0077b5" d="m21 21h-4v-6.75c0-1.06-1.19-1.94-2.25-1.94s-1.75 0.88-1.75 1.94v6.75h-4v-12h4v2c0.66-1.07 2.36-1.76 3.5-1.76 2.5 0 4.5 2.04 4.5 4.51v7.25m-14 0h-4v-12h4v12m-2-18a2 2 0 0 1 2 2 2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2 2 2 0 0 1 2 -2z"/></svg>'
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
.footer-icons {
    display: flex;
    justify-content: center;
    margin: 0 0 .5rem;
    padding: 0;
    list-style: none;

    li {
        margin: 0 .35rem;
        height: 32px;
        width: 32px;
    }
}
.made-with {
    display: flex;
    justify-content: center;
    margin: 1rem 0 0;
    padding: 0;
    list-style: none;

    svg {
        width: 18px;
        height: 18px;

        &.info path {
            fill: #444;
        }
    }

    li {
        display: flex;
        align-items: center;

        a {
            display: flex;
            align-items: center;
            margin: 0 .3rem;

            &:nth-last-child(3) {
                margin: 0 0 0 .5rem;
            }

            &.vite {
                margin-right: 0;
            }
        }
    }
}
</style>
