<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
            <router-link router-link to="/" class="navbar-brand">
                <!-- <span class="material-icons">home</span> -->
            </router-link><routes-link></routes-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <!-- <li>
                            <span class="material-icons">
                                <span class="material-symbols-outlined">
                                    settings
                                </span>
                                home
                            </span>
                        </li> -->

                    <li class="nav-item">
                        <router-link to="/" class="nav-link active" aria-current="page">
                            <span class="material-icons">home</span>
                        </router-link>

                    </li>
                    <li class="nav-item">
                        <router-link to="/about" class="nav-link active" aria-current="page">
                            <span class="material-icons">info</span>
                        </router-link>

                    </li>
                    <li class="nav-item">
                        <!-- Sustituimos la a del link html por router-link -->
                        <router-link to="/posts" class="nav-link active" aria-current="page">
                            <span class="material-icons">featured_play_list</span>
                        </router-link>

                    </li>
                    <li class="nav-item">
                        <!-- Sustituimos la a del link html por router-link -->
                        <router-link to="/nosotros" class="nav-link active" aria-current="page">
                            <span class="material-icons">featured_play_list</span>
                        </router-link>

                    </li>
                    

                </ul>
            </div>
        </div>
    </nav>
</template>