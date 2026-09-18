# cepbeyfixergadget<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <titlstyle.csse>CEPBEY FIXERGADGET SOLUTION SERVICE HP</title>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background: #f5f7fa;
    color: #222;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

/* HEADER */
header {
    background: #111827;
    color: white;
    text-align: center;
    padding: 45px 20px;
}

header h1 {
    font-size: 32px;
    margin-bottom: 8px;
}

header p {
    font-size: 18px;
}

/* NAVIGASI */
nav {
    background: #2563eb;
    padding: 15px 0;
    position: sticky;
    top: 0;
    z-index: 100;
}

nav .container {
    display: flex;
    justify-content: center;
    gap: 25px;
    flex-wrap: wrap;
}

nav a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

nav a:hover {
    text-decoration: underline;
}

/* HERO */
.hero {
    text-align: center;
    padding: 90px 20px;
    background: white;
}

.hero h2 {
    font-size: 40px;
    margin-bottom: 15px;
}

.hero p {
    max-width: 700px;
    margin: 0 auto 30px;
    font-size: 18px;
}

/* BUTTON */
.button {
    display: inline-block;
    background: #2563eb;
    color: white;
    padding: 13px 25px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
}

.button:hover {
    background: #1d4ed8;
}

/* SECTION */
section {
    padding: 70px 20px;
}

section h2 {
    text-align: center;
    margin-bottom: 35px;
    font-size: 30px;
}

/* SERVICES */
.services {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
}

.service {
    background: white;
    padding: 25px;
    border-radius: 12px;
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
}

.service h3 {
    margin-bottom: 10px;
}

/* ABOUT */
.about {
    background: white;
}

.about p {
    max-width: 800px;
    margin: auto;
    text-align: center;
}

/* CONTACT */
#kontak {
    text-align: center;
}

/* FOOTER */
footer {
    background: #111827;
    color: white;
    text-align: center;
    padding: 25px 10px;
}

/* TAMPILAN HP */
@media (max-width: 600px) {

    header h1 {
        font-size: 25px;
    }

    header p {
        font-size: 15px;
    }

    nav .container {
        gap: 15px;
    }

    .hero h2 {
        font-size: 30px;
    }

    .services {
        grid-template-columns: 1fr;
    }

    section {
        padding: 50px 15px;
    }
}
