import image from '@/'

<template>
    <div class="container">
        <div class=" box">
            <div class="box-color">
                <div class="text1">
                    <h1>
                        Olá!
                    </h1>
                </div>
                <div class="text2">
                    <h3>
                        Bem-vindo ao GestorFamiliar
                    </h3>
                </div>
                <div class="image">
                    <img src="/templates/finance-projeto1.png" alt="Imagem Projeto">
                </div>
                <div class="text3">
                    <p>
                        O GestorFamiliar é a solução completa para gestão financeira doméstica, desenvolvido para simplificar o controle de receitas, despesas e o planejamento do orçamento familiar.
                    </p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap');

* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

.container {
    background-color: #E4E4E4;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 98vh;
}

.box {
    background-color: #ffffff;
    border-radius: 5px;
    box-shadow: 10px 10px 35px rgba(0, 0, 0, 0.50), 0 9px 10px rgba(0, 0, 0, 0);
    width: 944px;
    height: 600px;
}

.box-color {
    background-color: #53B1E9;
    width: 480px;
    height: 600px;
    border-radius: 5px 0 0 5px;
}

.text1 {
    /* border: solid 2px greenyellow; */
    font-family: "Roboto", serif;
    font-size: 17px;
    padding-top: 81px;
    display: flex;
    justify-content: center;
}

.text2 {
    font-family: "Roboto", serif;
    font-size: 13px;
    margin-top: 15px;
    display: flex;
    justify-content: center;
}

.image {
    width: 321px;
    height: 288px;
    margin: auto;
    margin-top: 15px;
    display: flex;
    justify-content: center;
}

.text3 {
    font-family: "Roboto", serif;
    font-size: 14px;
    width: 321px;
    height: 56px;
    margin: auto;
    margin-top: 15px;
    display: flex;
    justify-content: center;
    text-align: justify;
}
</style>