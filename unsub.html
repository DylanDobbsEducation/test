<!DOCTYPE html>
<html>
<head>
    <title>Unsubscribe</title>
</head>
<body>
    <h1>Unsubscribe from Email Sequences</h1>
    <p>If you no longer wish to receive emails from us, please enter your email address and select the email sequences you want to unsubscribe from:</p>

    <form action="https://formspree.io/your-email@example.com" method="POST">
        <label for="email">Email Address:</label>
        <input type="email" id="email" name="email" required>
        <br>

        <input type="checkbox" id="cima" name="cima" value="CIMA">
        <label for="cima">CIMA</label>
        <br>

        <input type="checkbox" id="cpwa" name="cpwa" value="CPWA">
        <label for="cpwa">CPWA</label>
        <br>

        <input type="submit" value="Confirm">
    </form>

    <p id="confirmation-message"></p>

    <h2>Entered Emails:</h2>
    <ul id="entered-emails"></ul>

    <script>
        const enteredEmails = [];

        document.getElementById("confirm-button").addEventListener("click", function() {
            const email = document.getElementById("email").value;
            const cimaChecked = document.getElementById("cima").checked;
            const cpwaChecked = document.getElementById("cpwa").checked;

            let confirmationMessage = `You have successfully unsubscribed from the following email sequences:`;

            if (cimaChecked) {
                confirmationMessage += "\n- CIMA";
            }

            if (cpwaChecked) {
                confirmationMessage += "\n- CPWA";
            }

            if (cimaChecked || cpwaChecked) {
                confirmationMessage += `\n\nAn email confirmation has been sent to ${email}.`;
                enteredEmails.push(email);
                updateEnteredEmailsList();
            } else {
                confirmationMessage = "Please select at least one email sequence to unsubscribe from.";
            }

            document.getElementById("confirmation-message").innerText = confirmationMessage;
        });

        function updateEnteredEmailsList() {
            const enteredEmailsList = document.getElementById("entered-emails");
            enteredEmailsList.innerHTML = "";
            enteredEmails.forEach(email => {
                const listItem = document.createElement("li");
                listItem.textContent = email;
                enteredEmailsList.appendChild(listItem);
            });
        }
    </script>
</body>
</html>
