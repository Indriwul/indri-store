<template>
  <main>
    <nav class="navbar navbar-expand-lg navbar-light" style="background: #808080;">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>
  <div class="collapse navbar-collapse" id="navbarNav">
     <ul class="navbar-nav mr-auto">
                                <li class="nav-item active">
                                    <NuxtLink to="/" class="text-dark cd-md-3">
                                        Home
                                    </NuxtLink>
                                </li>
                                <li class="nav-item active">
                                    <NuxtLink to="/products" class="text-dark col-md-3">
                                        Product
                                    </NuxtLink>
                                </li>
                                <li class="nav-item active">
                                    <NuxtLink to="/contact" class="text-dark col-md-3">
                                        Contact
                                    </NuxtLink>
                                </li>
                            </ul>
  </div>
</nav>
  </main>
</template>