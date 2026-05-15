<script setup></script>
<template>
    <header>
        <nav class="navbar navbar-expand-lg decktop-navigation">
            <div class="container">
                <a class="navbar-brand flex-grow-1" href="#">
                    <img src="@/assets/img/logo.svg" alt="Nexcent" class="decktop-navigation__logo">

                </a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent"
                    aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul
                        class="navbar-nav me-auto mb-2 mb-lg-0 flex-grow-1 row-gap-2 column-gap-4 mt-4 mt-lg-0 align-items-center">
                        <li class="nav-item">
                            <a class="nav-link decktop-navigation__list-element_active" aria-current="page"
                                href="#">Home</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Service</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Feature</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Product</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Testimonial</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">FAQ</a>
                        </li>
                    </ul>
                    <div
                        class="d-flex gap-3 justify-content-lg-end justify-content-lg-center flex-grow-1 flex-column flex-lg-row">
                        <button class="button_light-s">Login</button>
                        <button class="button_primary-s">Sign up</button>
                    </div>
                </div>
            </div>
        </nav>
    </header>
</template>

<style scoped></style>