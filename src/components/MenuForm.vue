<template>
    <div>
        <Header/>
        <div class="formulaireMenu">
        <h1>Menu</h1>
        <form action="post" id="formMenu">
        <div class="firstLine">
            <div class="nameDiv">
                <p>Nom du plat:</p><br>
                <input type="text" name="name" placeholder="Nom du plat" id="nomDuPlat"><br>
            </div>
            <div class="prixDiv">
                <p>Prix:</p><br>
                <input type="text" name="prix" placeholder="x" id="prix"><br>
            </div>
            <button name="addImg" value="Submit">
                <p>Importer une photo</p>
            </button><br>
        </div>

        <div class="secondLine">
            <div class="descriptionDiv">
                <p>Description:</p><br>
                <textarea name="description" id="description" cols="30" rows="10"
                    style="resize: none;"></textarea><br>
            </div>
            <div class="categorieDiv">
                <p>Categorie:</p><br>
                <SELECT name="category" size="1">
                    <OPTION>lundi
                    <OPTION>mardi
                    <OPTION>mercredi
                    <OPTION>jeudi
                    <OPTION>vendredi
                    <OPTION>vendredi
                    <OPTION>vendredi
                    <OPTION>vendredi
                    <OPTION>vendredi
                    <OPTION>vendredi
                    <OPTION>vendredi
                    <OPTION>vendredi
                </SELECT>
            </div>
        </div>


        <button name="add" form="formMenu" value="Submit" class="addMenuBtn">Ajouter</button>
        </form>
    </div>

    <div class="listing">
        <div class="listContainer">
            <div class="listData">
                <p class="dishName">Plat1</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">15 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat2</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">52 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat3</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">35 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat4</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">25 Eur</p>
                <img src="#" alt="#" class="dishImg">
                
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
            </div>
            <div class="listData">
                <p class="dishName">Plat1</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">15 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat2</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">52 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat3</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">35 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat4</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">25 Eur</p>
                <img src="#" alt="#" class="dishImg">
                
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
            </div>
            <div class="listData">
                <p class="dishName">Plat1</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">15 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat2</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">52 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat3</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">35 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat4</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">25 Eur</p>
                <img src="#" alt="#" class="dishImg">
                
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
            </div>
            <div class="listData">
                <p class="dishName">Plat1</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">15 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat2</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">52 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat3</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">35 Eur</p>
                <img src="#" alt="#" class="dishImg">
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
                </div>
                <div class="listData">
                <p class="dishName">Plat4</p>
                <p class="dishCat">Categorie</p>
                <p class="dishPrice">25 Eur</p>
                <img src="#" alt="#" class="dishImg">
                
                <div class="editMode">
                <i class="far fa-edit"></i>
                <i class="far fa-trash-alt"></i>
                </div>
            </div>
        </div>
    </div>
    </div>
    
</template>

<script>
import Header from "@/components/Header.vue";
export default {
name: "MenuForm",
}
</script>

<style>

</style>
