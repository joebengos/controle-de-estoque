<template>
    <div class="text-center">
        <form action="" class="form-signin">
            <img class="mb-4" src="../assets/logo.png" alt="" width="72" height="72">
            <h1 class="h3 mb-3 font-weight-normal">Por favor faça seu login</h1>

            <label for="inputEmail" class="sr-only">Email address</label>
            <input type="email" id="inputEmail" class="form-control" placeholder="Email address" required="" autofocus="">

            <label for="inputPassword" class="sr-only">Password</label>
            <input type="password" id="inputPassword" class="form-control" placeholder="Password" required="">

            <div class="checkbox mb-3">
                <label>
                    <input type="checkbox" value="remember-me"> Manter logado
                </label>
            </div>

            <button class="btn btn-lg btn-primary btn-block" type="submit">Sign in</button>

            <p class="mt-5 mb-3 text-muted">© Controle de estoque - OCT | 2017-2019</p>
        </form>
    </div>
</template>

<style>
    .form-signin {
        max-width: 300px;
        margin: 0 auto;
    }
</style>


<script>


export default {
    name: 'FormLogin',
    props: {}
}
</script>
