<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Association AMPS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
            color: #333;
        }
        header {
            background-color: #337ab7;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }
        nav {
            background-color: #5bc0de;
            padding: 10px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        nav ul li {
            display: inline;
            margin-right: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: #fff;
            padding: 10px 20px;
            background-color: #337ab7;
            border-radius: 5px;
        }
        section {
            padding: 20px;
            background-color: #fff;
            margin: 20px;
            border-radius: 10px;
        }
        footer {
            background-color: #337ab7;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        .modal {
            display: none;
            position: fixed;
            z-index: 1;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            overflow: auto;
            background-color: rgba(0,0,0,0.5);
        }
        .modal-content {
            background-color: #fefefe;
            margin: 15% auto;
            padding: 20px;
            border: 1px solid #888;
            width: 80%;
            border-radius: 5px;
        }
        .close {
            color: #aaa;
            float: right;
            font-size: 28px;
            font-weight: bold;
        }
        .close:hover,
        .close:focus {
            color: black;
            text-decoration: none;
            cursor: pointer;
        }
        .photo-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 20px;
        }
        .photo {
            width: 30%;
            margin-bottom: 20px;
            border-radius: 5px;
            overflow: hidden;
            box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
            transition: 0.3s;
        }
        .photo:hover {
            box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
        }
        .logo-container {
            position: absolute;
            top: 20px;
            left: 20px;
        }
    </style>
</head>
<body>
    <div class="logo-container">
        <img src="file:///C:/Users/anischader/OneDrive/AMPS/Capture%20d'%C3%A9cran%202024-05-07%20130952.png" alt="Logo de l'association AMPS" width="100"/>
        <br/>
        <br/>
        <p>L'âge n'est qu'un numéro, l'amitié est éternelle</p>
    </div>
    <header>
        <h1>Association AMPS</h1>
        <p>Association pour l'Aide aux Personnes Âgées</p>
    </header>
    <nav>
        <ul>
            <li><a href="#presentation">Présentation</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="presentation">
        <h2>Présentation de l'association</h2>
        <p>L'association AMPS est dédiée à fournir une assistance et un soutien aux personnes âgées de notre communauté.</p>
        <p>Nous nous engageons à offrir des services de qualité et à promouvoir le bien-être des personnes âgées.</p>
        <button onclick="openModal('members')">Non membres</button>
        <button onclick="openModal('history')">Histoire</button>
    </section>
    <section id="services">
        <h2>Nos services</h2>
        <ul>
            <li>Aide à domicile</li>
            <li>Accompagnement médical</li>
            <li>Activités sociales et culturelles</li>
            <li>Programmes de prévention</li>
            <li>Et bien plus encore...</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Nous contacter</h2>
        <p>Adresse : 123 rue des moratas, Les yvline</p>
        <p>Téléphone : 01 23 45 67 89</p>
        <p>Email : contact@amps.org</p>
    </section>
    <footer>
        <p>&copy; 2024 Association AMPS. Tous droits réservés.</p>
    </footer>

    <!-- Modals -->
    <div id="membersModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('members')">&times;</span>
            <h2>Informations pour les non membres</h2>
            <p>Créateur de l'association : Anis Chader
            <br/>
               Le bénévole : Ayadi Rekik
               <br/>
               Le journaliste : Alexandre Dolo
               <br/>
               Le bénéficiaire :  Aymène Boukhariss  </div>
    </div>
    <div id="historyModal" class="modal">
        <div class="modal-content">
            <span class="close" onclick="closeModal('history')">&times;</span>
            <h2>Histoire de l'association</h2>
            <p>Cette association a été créée spécifiquement pour les personnes âgées, étant donné qu'elles sont seules et abandonnées par les personnes qui leur sont chères, malgré tous leurs efforts pour les rendre heureuses. Ma tante était complètement paralysée à cause de la maladie SEP, alors elle a été abandonnée par tout le monde, y compris son mari et ses enfants. Cela l'a rendue déprimée pendant de nombreuses années, puis la maladie l'a vaincue et elle est décédée. Nous avons appris plus tard que l'état psychologique est important pour les personnes âgées qui sont devenues âgées et vulnérables à la maladie. J'ai transformé mon chagrin pour ma tante en motivation et j'ai cherché des personnes pour m'aider à créer une association. On sait qu'au moins deux personnes le sont. nécessaire pour créer une association. J'ai trouvé un cofondateur, qui n'a pas hésité à m'aider, et grâce à lui nous avons réussi à étendre notre  réseau dans toute la France, et nous avons obtenu une aide considérable jusqu'à présent, et nous allons essayer de nous développer de plus en plus.</p>
        </div>
    </div>

    <!-- JavaScript -->
    <script>
        // Ouverture d'une fenêtre modale
        function openModal(id) {
            document.getElementById(id + 'Modal').style.display = "block";
        }

        // Fermeture d'une fenêtre modale
        function closeModal(id) {
            document.getElementById(id + 'Modal').style.display = "none";
        }
    </script>
</body>
</html>
