<script>
import logo from "$lib/assets/img/Destiney_image.jpg";
</script>


<body>
    <header>
    <img alt = "Destiney_image" src = "{logo}" height = "100" weight = "200">
    </header>
    <center><h1>FORMULAIRE</h1></center>
    <form>
        <label for="ville_input">Ville :</label><br>
        <input type="text"><br><br>

        <label for="date_input">Date arrivée:</label>
        <center><label for="date_input">Date fin:</label></center><br>
        <input type="date">
        <center><input type="date"></center><br>

        <label for="select_pays">Pays :</label><br>
        <select>
            <option value="pays1">Açores</option>
            <option value="pays2">Afghanistan</option>
            <option value="pays3">Afrique du Sud</option>
            <option value="pays4">Albanie</option>
            <option value="pays5">Algérie</option>
            <option value="pays6">Allemagne</option>
            <option value="pays7">Andorre</option>
            <option value="pays8">Anguilla</option>
            <option value="pays9">Antigua et Barbuda</option>
            <option value="pays10">Arabie Saoudite</option>
            <option value="pays11">Argentine</option>
            <option value="pays12">Arménie</option>
            <option value="pays13">Aruba</option>
            <option value="pays14">Australie</option>
            <option value="pays15">Autriche</option>
            <option value="pays16">Azerbaïdjan</option>
            <option value="pays17">Bahamas</option>
            <option value="pays"></option>
            <option value="pays"></option>
            <option value="pays"></option>
        </select><br><br>
    </form>
</body>

<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<a href="/about">about</a>