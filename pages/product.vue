<template>
 <div>
    <Header/>
    <ShopPage/>
    <Footer/>
    </div>
</template>
<script>
export default {
    head() {
        return {
            script: [
                {
                    src: "/assets/js/shop.js",
                    src: "/assets/feather/feather.min.js",
                    src: "/assets/fontawesome-free-5.15.0-web/js/all.js",
                },
            ],
            link: [
                { rel: "stylesheet", href: require("assets/css/styles.css") },
                { rel: "stylesheet", href: require("assets/fontawesome-free-5.15.0-web/css/all.css") },
                { rel: "icon", href: require("assets/logo.png") },
                { rel: "shortcut", href: require("assets/logo.png") },
                { rel: "apple-touch-icon", href: require("assets/logo.png") },
            ]
        };
    }
}
</script>