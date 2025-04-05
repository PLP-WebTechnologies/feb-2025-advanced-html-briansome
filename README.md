# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements and Forms</title>
</head>
<body>

    <header>
        <h1>Advanced HTML5 Elements</h1>
    </header>

    <main>
        <section>
            <h2>Orodha Iliyoagizwa (Nambari za Kirumi)</h2>
            <ol type="I">
                <li>Bidhaa Moja</li>
                <li>Bidhaa Mbili</li>
                <li>Bidhaa Tatu</li>
                <li>Bidhaa Nne</li>
                <li>Bidhaa Tano</li>
            </ol>
        </section>

        <section>
            <h2>Picha ya Nje</h2>
            <img src="https://images.pexels.com/photos/20787/pexels-photo.jpg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Mandhari nzuri">
        </section>

        <section>
            <h2>Jedwali la Mawasiliano</h2>
            <table>
                <thead>
                    <tr>
                        <th>Jina</th>
                        <th>Anwani</th>
                        <th>Simu</th>
                        <th>Barua Pepe</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>John Kamau</td>
                        <td>123 Barabara ya Uhuru</td>
                        <td>123-456-7890</td>
                        <td>john.kamau@example.com</td>
                    </tr>
                    <tr>
                        <td>Jane Wanjiru</td>
                        <td>456 Mtaa wa Acacia</td>
                        <td>987-654-3210</td>
                        <td>jane.wanjiru@example.com</td>
                    </tr>
                    <tr>
                        <td>David Otieno</td>
                        <td>789 Njia ya Mbuyu</td>
                        <td>555-123-4567</td>
                        <td>david.otieno@example.com</td>
                    </tr>
                    <tr>
                        <td>Sarah Akinyi</td>
                        <td>101 Barabara ya Mlimani</td>
                        <td>111-222-3333</td>
                        <td>sarah.akinyi@example.com</td>
                    </tr>
                    <tr>
                        <td>Michael Kiprop</td>
                        <td>202 Barabara ya Mtaa wa Mti</td>
                        <td>444-555-6666</td>
                        <td>michael.kiprop@example.com</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <section>
            <h2>Fomu ya Usajili</h2>
            <form action="/submit-registration" method="post">
                <label for="jina">Jina:</label>
                <input type="text" id="jina" name="jina" placeholder="Ingiza jina lako" required><br><br>

                <label for="barua_pepe">Barua Pepe:</label>
                <input type="email" id="barua_pepe" name="barua_pepe" placeholder="Ingiza barua pepe yako" required><br><br>

                <label for="neno_siri">Neno Siri:</label>
                <input type="password" id="neno_siri" name="neno_siri" placeholder="Ingiza neno siri yako" required minlength="8"><br><br>

                <label for="tarehe_kuzaliwa">Tarehe ya Kuzaliwa:</label>
                <input type="date" id="tarehe_kuzaliwa" name="tarehe_kuzaliwa"><br><br>

                <label for="nchi">Nchi:</label>
                <select id="nchi" name="nchi">
                    <option value="kenya">Kenya</option>
                    <option value="tanzania">Tanzania</option>
                    <option value="uganda">Uganda</option>
                    <option value="rwanda">Rwanda</option>
                </select><br><br>

                <p>Jinsia:</p>
                <input type="radio" id="mwanaume" name="jinsia" value="mwanaume">
                <label for="mwanaume">Mwanaume</label><br>
                <input type="radio" id="mwanamke" name="jinsia" value="mwanamke">
                <label for="mwanamke">Mwanamke</label><br>
                <input type="radio" id="nyingine" name="jinsia" value="nyingine">
                <label for="nyingine">Nyingine</label><br><br>

                <p>Mapenzi:</p>
                <input type="checkbox" id="michezo" name="mapenzi" value="michezo">
                <label for="michezo">Michezo</label><br>
                <input type="checkbox" id="muziki" name="mapenzi" value="muziki">
                <label for="muziki">Muziki</label><br>
                <input type="checkbox" id="kusoma" name="mapenzi" value="kusoma">
                <label for="kusoma">Kusoma</label><br><br>

                <input type="submit" value="Jisajili">
            </form>
        </section>

    </main>

    <footer>
        <p>&copy; 2024 Mifano ya HTML5 ya Juu</p>
    </footer>

</body>
</html>
