<template>

    <div class="containerCV" style="animation: fadeIn 1s ease-in-out;">
        <div class="content-grid">
            <div class="content header" id="about">

                <h1>Marat Davletshin</h1>

                <p><i class="fa fa-mars" aria-hidden="true"></i> Software Developer</p>
                <p><i class="fa fa-phone" aria-hidden="true"></i> <a href="https://wa.me/4367761782017" class="whatsapp-link">+43 677 617 82 017</a></p>
                <p><i class="fa fa-address-card"></i> Wien Österreich</p>
                <p><i class="fa fa-envelope" aria-hidden="true"></i> <a href="mailto:davletshin081180@gmail.com">davletshin081180@gmail.com</a></p>
                <p><a href="https://www.github.com/nexoc"> www.github</a></p>              
                
            </div>
			
			<div class="content photo" id="photo">		
                <img class="photo"  alt="photo" src="../assets/photo.jpg" width="350" height="420">
			</div>

            <div class="content experience" id="experience">
                <h2>Erfahrung</h2>
                <ul>
                    <li>06.2022 - 08.2022: Software Entwickler Praktikant, Berlin, Deutschland, Digital.Wolff, Plötz & Co GmbH</li>
                    <li>Entwicklung eines Python-Mikroservices zur Datentransformation von JSON-Dateien in eine Postgresql-Datenbank. Implementierung verschiedener Zugriffsrechte (Admin, Moderator, Mitarbeiter) für gespeicherte Daten wie Fotos, Videos, Geolokation und Zeit. Administration der Postgresql-Datenbank. Frontend-Programmierung in JavaScript (Vue) für eine webbasierte Version zur Erfassung und Übermittlung von Fotos, Videos, Geolokationsdaten und Zeitstempeln auf den Server.</li>
                </ul>
                <ul>
                    <li>2006-2020: Balletttänzer Wien, Österreich, Wiener Staatsoper</li>
                    <li>2004-2006: Balletttänzer Leipzig, Deutschland, Leipziger Opernhaus</li>
                    <li>2000-2004: Balletttänzer Moskau, Russland, Das Staatliche Akademische Theater des klassischen Balletts</li>
                </ul>
            </div>

            <div class="content education" id="education">
                <h2>Bildung und Qualifikationen:</h2>
                <ul>
                    <li><strong>2020 – 10.2023:</strong> HTL TGM Kolleg für Wirtschaftsingenieure – Betriebsinformatik Wien</li>
                    <li>Diplomarbeit: Entwicklung eines naturwissenschaftlichen Lernprogramms für die HTL unter Verwendung von Python, mit Schwerpunkt auf Mathematik. Umgesetzt mithilfe von Python, PyQt5 und matplotlib, einschließlich der Integration von matplotlib.animation für eine interaktive Lernerfahrung.</li>
                    <li>2002-2004: Russische Akademie für Theaterkunst RATI, Staatliches Institut für Theaterkunst, Moskau, Russland</li>
                    <li>1997-2000: Das Bolschoi Theater Ballett Academy, Berufsbildende Schule mit Matura, Moskau</li>
                </ul>
            </div>

            <div class="content skills" id="skills">
                <h2 id="tech-skills-title">Tech skills:</h2>
                <table id="tech-skills-table">
                    <tr>
                        <td id="frontend-category">Frontend</td>
                        <td id="frontend-skills">
                            <ul id="frontend-skills-list">
                                <li id="frontend-html">HTML</li>
                                <li id="frontend-css">CSS</li>
                                <li id="frontend-js">JS (VueJS)</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td id="backend-category">Backend</td>
                        <td id="backend-skills">
                            <ul id="backend-skills-list">
                                <li id="backend-java">Java
                                    <ul id="java-skills-list">
                                        <li id="spring-core">Spring Core, Maven, Lombok, JDBC API, JDBC Template</li>
                                        <li id="spring-mvc">Spring MVC, Spring Data JPA, Hibernate, Spring Boot</li>
                                        <li id="rest-api">REST API using Spring Boot</li>
                                        <li id="spring-security">Spring Security with JWT, CORS, CSRF</li>
                                    </ul>
                                </li>
                                <li id="backend-python">Python: Django</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td id="sql-category">SQL</td>
                        <td id="sql-skills">
                            <ul id="sql-skills-list">
                                <li id="sql-databases">PostgreSQL, SQLite, H2</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td id="devops-category">DevOps</td>
                        <td id="devops-skills">
                            <ul id="devops-skills-list">
                                <li id="linux-admin">Linux System Administrator on Debian, Ubuntu</li>
                                <li id="docker">Docker, Docker Compose</li>
                                <li id="nginx">Nginx</li>
                            </ul>
                        </td>
                    </tr>
                    <tr>
                        <td id="other-category">Others</td>
                        <td id="other-skills">
                            <ul id="other-skills-list">
                                <li id="git">Git</li>
                                <li id="ms-office">MS-Office</li>
                            </ul>
                        </td>
                    </tr>
                </table>
            </div>

            <div class="content languages" id="languages">
                <h2>Sprachen</h2>
                <p>Deutsch (C1)</p>
                <p>Englisch (B2)</p>
				<p>Russisch (Muttersprache)</p>
            </div>
        </div>
    </div>

</template>

<style scoped>
        .containerCV {
            width: 100%;
            padding: 0;
			margin-left: 0;
            animation: fadeIn 1s ease-in-out;
        }

        .content-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            grid-gap: 20px;
        }

        .content {
            padding: 5%;
            border-radius: 10px;
			transition: background-color 0.5s ease-in-out;
			justify-content: center; /* Horizontal center alignment */
			align-items: center; /* Vertical center alignment */
			flex-direction: column; /* Arranged vertically */
			min-height: 20vh; /* Height equals viewport height */
			background-color: #E2E2E2; 
        }
		
		.photo {
			display: flex;
		}
				
		.content:hover {
			background-color: #333;
			color: #ffffff;
			min-height: 20vh; /* Height equals viewport height */
			font-size: 150%;
			cursor: pointer;
		}		
		

        /* Additional styling for the .container class */
        @media (min-width: 768px) {
            .container {
                margin-left: 100px;
                margin-right: 100px;
            }
        }
</style>