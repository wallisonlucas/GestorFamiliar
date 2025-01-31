<template>
    <div class="box-container">
        <div class="form-login">
            <form action="#">
                <div class="form-title">
                    <div class="text1-login">
                        <h2>
                            Faça seu login
                        </h2>
                    </div>
                </div>
                <div class="input-login">
                    <div class="input-box1">
                        <label for="email">E-mail</label>
                        <i class="fa-solid fa-envelope"></i>
                        <input  type="email" name="email" v-model="email" placeholder="Digite seu e-mail" required autocomplete="off"/>
                    </div>
                    <div class="input-box2">
                        <label for="password">Senha</label>
                        <i class="fa-solid fa-lock"></i>
                        <input type="password" name="password" v-model="senha" placeholder="Digite sua senha" required autocomplete="off"/>
                    </div>
                </div>
                <div class="recover">
                    <a href="#">Esqueceu a senha?</a>
                </div>
                <div class="button-login">
                    <div class="button-enter">            
                        <button><a href="#">ENTRAR</a></button>
                    </div>
                    <div class="button-register">
                        <button><a href="#">REGISTRAR</a></button>
                    </div>
                </div>
            </form>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Login'
    }
</script>

<style scouped>

.box-container {
    width: 465px;
    height: 600px;
    top: 0;
    right: 0;
    position: absolute;
}

.form-title{
    display: flex;
    justify-content: center;
    margin-top: 137px;
}

.form-login {
    display: flex;
    align-items: center;
    flex-direction: column;
}

.input-login {
    margin-top: 32px;
    display: flex;
    flex-direction: column;
}

.input-login input::placeholder {
    color: #828282;
    font-weight: 400;
    /* padding: 45px; */
}

.input-box1 {
    display: flex;
    flex-direction: column;
}

.input-box2 {
    display: flex;
    flex-direction: column;
    margin-top: 20px;
}

.input-login label {
    width: 60px;
    height: 22px;
    font-size: 13px;
    font-weight: 600;
    padding: 5px;
}

.input-login input {
    background-color: #F3F3F3;
    width: 304px;
    height: 36px;
    border: solid 1px #000000;
    border-radius: 5px;
    padding: 10px 40px;
}

.input-login i {
    color: #B1B1B1;
    font-size: 14px;
    display: flex;
    position: absolute;
    margin-top: 33px;
    margin-left: 16px;
}

.recover a {
    text-decoration: none;
    font-size: 12px;
    font-weight: 500;
    display: flex;
    width: 131px;
    height: 16px;
    font-size: 12px;
    color: #000000;
    justify-content: flex-end;
    margin-left: 170px;
    margin-top: 5px;
}

.button-login {
    display: flex;
    flex-direction: column;
    margin-bottom: 9px;
}

.button-login button {
    width: 304px;
    height: 36px;
    border: solid 1px #000000;
    border-radius: 5px;
}

.button-enter button {
    margin-top: 48px;
    color: #53B1E9;
    background-color: #FFFFFF;
    font-weight: bolder;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
}

.button-enter button:hover {
    background-color: #ebebeb;
}

.button-enter a {
    color: #53B1E9;
    text-decoration: none;
    font-size: 13px;
}

.button-register button {
    margin-top: 9px;
    color: #FFFFFF;
    background-color: #53B1E9;
    font-weight: bolder;
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
}

.button-register button:hover {
    background-color: #3fa0d8;
}

.button-register a {
    color: #ebebeb;
    text-decoration: none;
    font-size: 13px;
}

</style>