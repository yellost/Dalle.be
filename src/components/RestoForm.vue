<template>
    <div>
        <main class="RestoAdmin">    
    <h2>Nouveau Restaurant</h2>
    <section class="total">
        <section>
            <div class="resto">
                <div class="rue-2">
                    <label for="name">
                        <p>Nom</p>
                    </label>
                    <input type="text" name="name" id="name" required autofocus maxlength="3" autocomplete="name">
                </div>
                <div class="rue">
                    <div class="rue-1">
                        <label for="rue">
                            <p>Rue</p>
                        </label>
                        <input type="text" name="rue" id="rue" required autofocus maxlength="3" autocomplete="name">
                    </div>
                    <div class="rue-1">
                        <Label>
                            <p>N°</p>
                        </Label><input type="text" pattern="[000]" title="Five digit zip code" />
                    </div>
                </div>
                <div class="rue">
                        <div class="rue-1">
                                <Label>
                                    <p>Code Postal</p>
                                </Label><input type="text" pattern="[0-9]{5}" title="Five digit zip code" />
                            </div>
                            <div class="rue-1">
                                    <Label>
                                        <p>Ville</p>
                                    </Label><input type="text" id="city" required autofocus maxlength="15"  title="City" />
                                </div>
                </div>
                <div class="rue-2">
                    <label for="tel">
                        <p>Téléphone</p>
                    </label>
                    <input type="tel" name="tel" id="tel" placeholder="Votre numéro de Téléphone">
                </div>
                <div class="rue-2">
                    <label for="name">
                        <p>Email</p>
                    </label>
                    <input type="email" name="email" id="email" placeholder="Ex:google@nadia.com">
                </div>
              <div class="rue-2">
                <button>
                    Enregistrer
                </button>
              </div>
            </div>
        </section>
        <div class="check">
            <h2>Type de Cuisine</h2>
            <div class="check-1">
                <form action="/action_page.php" method="get" class="form-1">
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Française"> Française<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Italienne"> Italienne<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Portugaise"> Portugaise<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Tapas"> Tapas<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Marocaine"> Marocaine<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Africaine"> Africaine<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Libanaise"> Libanaise<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Turque"> Turque<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Indienne"> Indienne<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Chinoise"> Chinoise<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Vietnamienne"> Vietnamienne<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Coréenne"> Coréenne<br>
                   </div>
                   <div class="test">
                        <input type="checkbox" name="cuisine" value="Japonaise"> Japonaise<br>
                   </div> 
                   
                   
                </form>
            </div>
        </div>
        <div class="foto">
            <button>Importer une photo</button>
            <img src="img/chair-cutlery-diner-941861.jpg" alt="resto">
        </div>
    </section>
</main>
    </div>
</template>

<script>

export default {
name: "RestoForm",
components:{
Header
}
}
</script>

<style>

</style>
