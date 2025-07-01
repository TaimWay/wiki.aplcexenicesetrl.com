<script setup>
</script>

<template>
    <nav class="main-nav">
        <div class="main-nav-left">
            <img src="/assets/wiki/image/wiki-logo.svg" class="main-nav-wiki-logo">
            <span class="main-nav-wiki-title">APlcexenicesetrl Wiki</span>
        </div>
        <ul class="main-nav-right">
            <li class="main-nav-list">
                <div class="main-nav-list-head">
                    <img src="/assets/wiki/image/main-nav/home/home-page.png">
                    <span>Home</span>
                </div>
                <div class="main-nav-list-item">
                    <ul>
                        <li>
                            <img src="/assets/wiki/image/main-nav/home/home-page.png">
                            <span>Home Page</span>
                        </li>
                        <li>
                            <img src="/assets/wiki/image/main-nav/home/home-page.png">
                            <span>Home Page</span>
                        </li>
                    </ul>
                </div>

            </li>

        </ul>
    </nav>
    <main>

    </main>
</template>

<style module src="/assets/wiki/wiki-style.css"></style>

<style scoped>
.main-nav {
    width: 100vw;
    height: 50px;
    padding: 5px;

    position: fixed;
    left: 0;
    top: 0;

    background-color: var(--main-nav-background);
    border: 1px solid var(--main-nav-border);
    border-radius: 10px;

    display: flex;
}

.main-nav .main-nav-left {
    margin-left: 20px;
    display: flex;
    align-items: center;
    gap: 5px;
}

.main-nav .main-nav-wiki-logo {
    width: var(--main-nav-wiki-logo-size);
    height: var(--main-nav-wiki-logo-size);
}

.main-nav .main-nav-wiki-title {
    font-size: 20px;
    font-weight: bold;
    color: var(--main-nav-wiki-title-color);
}

.main-nav .main-nav-right {
    display: flex;
    gap: 10px;
    margin-left: auto;
    margin-right: 20px;
    list-style: none;
}

.main-nav .main-nav-right .main-nav-list {
    background-color: transparent;
    border: none;
    color: var(--main-nav-list-color);
}

.main-nav .main-nav-right .main-nav-list .main-nav-list-head,
.main-nav .main-nav-right .main-nav-list .main-nav-list-item ul li {
    display: flex;
    justify-content: center;
    gap: 10px;
}

.main-nav .main-nav-right .main-nav-list .main-nav-list-item {
    transform: translateY(10px);
}

.main-nav .main-nav-right .main-nav-list .main-nav-list-item ul li {
    padding: 10px 0;
}

.main-nav .main-nav-right .main-nav-list img {
    width: var(--main-nav-list-logo-size);
    height: var(--main-nav-list-logo-size);
}

.main-nav .main-nav-right .main-nav-list span {
    font-size: 20px;
}
</style>
