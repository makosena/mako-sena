

<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mako service de paiement</title>
    <!-- Chargement de Tailwind CSS via CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configuration de la police Inter pour une meilleure lisibilité -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800 antialiased">

    <!-- En-tête de la page -->
    <header class="bg-gradient-to-r from-blue-500 to-purple-600 text-white p-6 shadow-lg rounded-b-xl">
        <div class="container mx-auto flex flex-col md:flex-row justify-between items-center">
            <h1 class="text-4xl font-extrabold mb-2 md:mb-0">Mako Service de Paiement</h1>
            <p class="text-lg opacity-90">Votre solution de paiement rapide et sécurisée.</p>
        </div>
    </header>

    <!-- Barre de navigation -->
    <nav class="bg-gray-800 p-4 shadow-md rounded-t-xl mx-auto mt-4 w-11/12 md:w-4/5">
        <ul class="flex flex-wrap justify-center space-x-4 md:space-x-8">
            <li><a href="#accueil" class="text-white hover:text-blue-300 transition duration-300 ease-in-out font-medium text-lg">Accueil</a></li>
            <li><a href="#fonctionnalites" class="text-white hover:text-blue-300 transition duration-300 ease-in-out font-medium text-lg">Fonctionnalités</a></li>
            <li><a href="#services" class="text-white hover:text-blue-300 transition duration-300 ease-in-out font-medium text-lg">Nos Services</a></li>
            <li><a href="#paiement-carte" class="text-white hover:text-blue-300 transition duration-300 ease-in-out font-medium text-lg">Paiement par Carte</a></li>
            <li><a href="#points-depot" class="text-white hover:text-blue-300 transition duration-300 ease-in-out font-medium text-lg">Points de Dépôt</a></li>
            <li><a href="#assistant" class="text-white hover:text-blue-300 transition duration-300 ease-in-out font-medium text-lg">Assistant ✨</a></li>
            <li><a href="#contact" class="text-white hover:text-blue-300 transition duration-300 ease-in-out font-medium text-lg">Contact</a></li>
        </ul>
    </nav>

    <!-- Contenu principal -->
    <main class="container mx-auto my-8 p-6 bg-white rounded-lg shadow-xl">

        <!-- Section Accueil -->
        <section id="accueil" class="mb-12">
            <p class="text-lg leading-relaxed mb-4">
                Nous achetons des recharges prépayées aux particuliers à un bon prix.
            </p>
            <p class="text-base leading-relaxed">
                Chaque élément est pensé pour être réactif, s'adaptant parfaitement à toutes les tailles d'écran,
                des ordinateurs de bureau aux appareils mobiles.
            </p>
            <div class="mt-6 flex justify-center">
                <img src="https://placehold.co/600x300/ADD8E6/000000?text=Paiement+Securise" alt="Image d'accueil" class="rounded-lg shadow-md max-w-full h-auto">
            </div>
        </section>

        <!-- Section Fonctionnalités -->
        <section id="fonctionnalites" class="mb-12">
            <h2 class="text-3xl font-bold text-blue-600 mb-4 border-b-2 pb-2 border-blue-200">Nos Fonctionnalités Clés</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Carte de fonctionnalité 1 -->
                <div class="bg-blue-50 p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-blue-700 mb-2">Transactions Rapides</h3>
                    <p class="text-gray-700">Effectuez vos paiements en quelques secondes, sans tracas.</p>
                </div>
                <!-- Carte de fonctionnalité 2 -->
                <div class="bg-purple-50 p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-purple-700 mb-2">Sécurité Avancée</h3>
                    <p class="text-gray-700">Vos données sont protégées par les dernières technologies de cryptage.</p>
                </div>
                <!-- Carte de fonctionnalité 3 -->
                <div class="bg-green-50 p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-green-700 mb-2">Support 24/7</h3>
                    <p class="text-gray-700">Notre équipe est disponible à tout moment pour vous assister.</p>
                </div>
            </div>
        </section>

        <!-- Nouvelle Section Services Spécifiques -->
        <section id="services" class="mb-12">
            <h2 class="text-3xl font-bold text-blue-600 mb-4 border-b-2 pb-2 border-blue-200">Nos Services de Paiement</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-2 gap-6">
                <!-- Recharge Neosurf -->
                <div class="bg-yellow-50 p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-yellow-700 mb-2">Recharge Neosurf</h3>
                    <p class="text-gray-700">Rechargez facilement vos cartes Neosurf directement depuis notre plateforme, pour des paiements en ligne anonymes et sécurisés.</p>
                </div>
                <!-- PCS Mastercard -->
                <div class="bg-red-50 p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-red-700 mb-2">PCS Mastercard</h3>
                    <p class="text-gray-700">Gérez et rechargez votre carte PCS Mastercard en toute simplicité, pour vos achats quotidiens et en ligne.</p>
                </div>
                <!-- Paiement via PayPal -->
                <div class="bg-indigo-50 p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-indigo-700 mb-2">Paiement via PayPal</h3>
                    <p class="text-gray-700">Connectez votre compte PayPal pour des paiements rapides et protégés, sans partager vos informations bancaires.</p>
                </div>
                <!-- Réception de Virement -->
                <div class="bg-teal-50 p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-teal-700 mb-2">Réception de Virement</h3>
                    <p class="text-gray-700">Recevez des virements bancaires directement sur votre compte Mako, avec des notifications en temps réel.</p>
                </div>
            </div>
        </section>

        <!-- Nouvelle Section: Paiement par Carte Bancaire -->
        <section id="paiement-carte" class="mb-12">
            <h2 class="text-3xl font-bold text-blue-600 mb-4 border-b-2 pb-2 border-blue-200">Paiement par Carte Bancaire</h2>
            <p class="text-lg leading-relaxed mb-4">
                Effectuez vos paiements en toute sécurité avec votre carte bancaire (Visa, Mastercard, etc.).
            </p>
            <div class="bg-blue-50 p-6 rounded-lg shadow-md">
                <form class="space-y-4">
                    <div>
                        <label for="cardNumber" class="block text-sm font-medium text-gray-700">Numéro de carte</label>
                        <input type="text" id="cardNumber" name="cardNumber" class="mt-1 block w-full p-3 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm" placeholder="XXXX XXXX XXXX XXXX" maxlength="19">
                    </div>
                    <div class="grid grid-cols-2 gap-4">
                        <div>
                            <label for="expiryDate" class="block text-sm font-medium text-gray-700">Date d'expiration (MM/AA)</label>
                            <input type="text" id="expiryDate" name="expiryDate" class="mt-1 block w-full p-3 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm" placeholder="MM/AA" maxlength="5">
                        </div>
                        <div>
                            <label for="cvv" class="block text-sm font-medium text-gray-700">CVV</label>
                            <input type="text" id="cvv" name="cvv" class="mt-1 block w-full p-3 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm" placeholder="XXX" maxlength="4">
                        </div>
                    </div>
                    <button type="submit" class="w-full px-6 py-3 bg-blue-600 text-white font-semibold rounded-md shadow-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 transition duration-300 ease-in-out">
                        Payer maintenant
                    </button>
                </form>
            </div>
        </section>

        <!-- Nouvelle Section: Points de Dépôt des Recharges -->
        <section id="points-depot" class="mb-12">
            <h2 class="text-3xl font-bold text-blue-600 mb-4 border-b-2 pb-2 border-blue-200">Où Déposer Vos Recharges Neosurf & PCS</h2>
            <p class="text-lg leading-relaxed mb-4">
                Pour vendre vos recharges Neosurf et PCS Mastercard à Mako Service de Paiement,
                nous vous offrons plusieurs options pratiques.
            </p>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Option 1: Dépôt en Ligne (via contact) -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-gray-700 mb-2">Dépôt en Ligne</h3>
                    <p class="text-gray-700">
                        Contactez-nous via le formulaire ci-dessous ou par téléphone pour organiser un dépôt rapide et sécurisé de vos codes de recharges.
                        Nous vous guiderons à travers le processus.
                    </p>
                </div>
                <!-- Option 2: Points de Dépôt Physiques (à préciser) -->
                <div class="bg-gray-50 p-6 rounded-lg shadow-md hover:shadow-lg transition duration-300 ease-in-out transform hover:-translate-y-1">
                    <h3 class="text-xl font-semibold text-gray-700 mb-2">Points de Dépôt Physiques</h3>
                    <p class="text-gray-700">
                        Nous disposons de "chambres" ou points de collecte désignés dans certaines zones.
                        Veuillez nous contacter pour obtenir la liste des adresses et les horaires de dépôt disponibles près de chez vous.
                    </p>
                </div>
            </div>
            <p class="text-base leading-relaxed mt-4">
                Notre objectif est de vous offrir la meilleure flexibilité pour vendre vos recharges prépayées.
            </p>

            <!-- Nouveau champ pour le code PIN du ticket -->
            <div class="mt-8 bg-blue-50 p-6 rounded-lg shadow-md">
                <h3 class="text-xl font-semibold text-blue-700 mb-4">Entrez votre code PIN de ticket</h3>
                <div class="space-y-4">
                    <div>
                        <label for="ticketPin" class="block text-sm font-medium text-gray-700">Code PIN du ticket (Neosurf ou PCS)</label>
                        <input type="text" id="ticketPin" name="ticketPin" class="mt-1 block w-full p-3 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm" placeholder="Ex: XXXXXXXXXXXXXXXX">
                    </div>
                    <button type="button" class="w-full md:w-auto px-6 py-3 bg-blue-600 text-white font-semibold rounded-md shadow-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 transition duration-300 ease-in-out">
                        Valider le code PIN
                    </button>
                </div>
            </div>
        </section>

        <!-- Nouvelle Section: Assistant Virtuel LLM -->
        <section id="assistant" class="mb-12">
            <h2 class="text-3xl font-bold text-blue-600 mb-4 border-b-2 pb-2 border-blue-200">Assistant Virtuel ✨</h2>
            <p class="text-lg leading-relaxed mb-4">
                Posez vos questions sur Mako Service de Paiement et obtenez des réponses instantanées de notre assistant intelligent.
            </p>
            <div class="bg-gray-50 p-6 rounded-lg shadow-md">
                <label for="questionInput" class="block text-sm font-medium text-gray-700 mb-2">Votre question :</label>
                <textarea id="questionInput" class="mt-1 block w-full p-3 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm" rows="3" placeholder="Ex: Comment fonctionne la recharge Neosurf ?"></textarea>
                <button id="askButton" class="mt-4 w-full md:w-auto px-6 py-3 bg-purple-600 text-white font-semibold rounded-md shadow-md hover:bg-purple-700 focus:outline-none focus:ring-2 focus:ring-purple-500 focus:ring-offset-2 transition duration-300 ease-in-out">
                    Demander à l'Assistant ✨
                </button>
                <div id="loadingIndicator" class="mt-4 text-center text-gray-600 hidden">
                    Chargement de la réponse...
                </div>
                <div id="responseOutput" class="mt-6 p-4 bg-white border border-gray-200 rounded-md shadow-sm text-gray-800 whitespace-pre-wrap">
                    <!-- La réponse de l'assistant apparaîtra ici -->
                </div>
            </div>
        </section>

        <!-- Section Contact -->
        <section id="contact">
            <h2 class="text-3xl font-bold text-blue-600 mb-4 border-b-2 pb-2 border-blue-200">Contactez-nous</h2>
            <form class="space-y-4">
                <div>
                    <label for="name" class="block text-sm font-medium text-gray-700">Nom</label>
                    <input type="text" id="name" name="name" class="mt-1 block w-full p-3 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm" placeholder="Votre nom">
                </div>
                <div>
                    <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
                    <input type="email" id="email" name="email" class="mt-1 block w-full p-3 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm" placeholder="votre.email@example.com">
                </div>
                <div>
                    <label for="message" class="block text-sm font-medium text-gray-700">Message</label>
                    <textarea id="message" name="message" rows="5" class="mt-1 block w-full p-3 border border-gray-300 rounded-md shadow-sm focus:ring-blue-500 focus:border-blue-500 sm:text-sm" placeholder="Votre message..."></textarea>
                </div>
                <button type="submit" class="w-full md:w-auto px-6 py-3 bg-blue-600 text-white font-semibold rounded-md shadow-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2 transition duration-300 ease-in-out">
                    Envoyer le Message
                </button>
            </form>
        </section>

    </main>

    <!-- Pied de page -->
    <footer class="bg-gray-900 text-white p-6 text-center mt-8 rounded-t-xl">
        <p class="text-sm">&copy; 2025 Mako Service de Paiement. Tous droits réservés.</p>
        <div class="flex justify-center space-x-4 mt-2">
            <a href="#" class="text-gray-400 hover:text-white transition duration-300 ease-in-out">Politique de confidentialité</a>
            <a href="#" class="text-gray-400 hover:text-white transition duration-300 ease-in-out">Conditions d'utilisation</a>
        </div>
    </footer>

    <script>
        document.getElementById('askButton').addEventListener('click', async () => {
            const questionInput = document.getElementById('questionInput');
            const responseOutput = document.getElementById('responseOutput');
            const loadingIndicator = document.getElementById('loadingIndicator');
            const userQuestion = questionInput.value.trim();

            if (!userQuestion) {
                responseOutput.textContent = "Veuillez poser une question.";
                return;
            }

            loadingIndicator.classList.remove('hidden'); // Afficher l'indicateur de chargement
            responseOutput.textContent = ''; // Effacer la réponse précédente

            try {
                let chatHistory = [];
                // Contextualize the LLM to answer about Mako's services
                const context = `Vous êtes un assistant virtuel pour Mako Service de Paiement. Mako achète des recharges prépayées (Neosurf, PCS Mastercard) aux particuliers à un bon prix, offre la réception de virements et gère les paiements via PayPal. Mako a des points de dépôt physiques ("chambres") et des options de dépôt en ligne. Répondez aux questions des utilisateurs en vous basant sur ces informations. Soyez concis et utile.`;
                chatHistory.push({ role: "user", parts: [{ text: context + "\n\nQuestion: " + userQuestion }] });

                const payload = { contents: chatHistory };
                const apiKey = ""; // Laissez la clé API vide, elle sera fournie par l'environnement Canvas
                const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });

                const result = await response.json();

                if (result.candidates && result.candidates.length > 0 &&
                    result.candidates[0].content && result.candidates[0].content.parts &&
                    result.candidates[0].content.parts.length > 0) {
                    const text = result.candidates[0].content.parts[0].text;
                    responseOutput.textContent = text;
                } else {
                    responseOutput.textContent = "Désolé, je n'ai pas pu obtenir de réponse. Veuillez réessayer.";
                    console.error("Erreur de l'API Gemini:", result);
                }
            } catch (error) {
                responseOutput.textContent = "Une erreur est survenue lors de la communication avec l'assistant.";
                console.error("Erreur de fetch:", error);
            } finally {
                loadingIndicator.classList.add('hidden'); // Cacher l'indicateur de chargement
            }
        });
    </script>

</body>
</html>
