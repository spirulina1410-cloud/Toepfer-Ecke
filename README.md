Neuen brand anlegen: das oben anhängen mit neuer zahl

<h2 class="ausklappen">
    Brand 3 ▼
</h2>
<div id="brand3" class="ausklapp-bereich"></div>

Ergänzen: erstelleBrand(3, 29);


Notizen
function notizFuerBild(brand, nummer) {

    const notizen = {

        "B3 Stück 6": "Von Jette und mir gemacht",
        "B3 Stück 7": "Von Jette gemacht",
        "B3 Stück 10": "Niedrigbrand",
        "B3 Stück 11": "Niedrigbrand"
    };
    return notizen[`B${brand} Stück ${nummer}`] || "";
}

Galerie
erstelleGalerie(5);
