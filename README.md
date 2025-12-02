# p5_2
index.html
[index 2 p5_2.html](https://github.com/user-attachments/files/23883275/index.2.p5_2.html)
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
   <link href="https://fonts.googleapis.com/css?family=Oswald:wght@200..700&family" rel="stylesheet">
   <link href="https://fonts.googleapis.com/css?family=Outfit:wght@100..900&" rel="stylesheet">
   <link href="https://fonts.googleapis.com/css2?family= Purple+Purse&family=Roboto+Slab:wght@100..900&family=Roboto:ital,wght@0,100..900;1,100..900&family" rel='stylesheet'>
    <link href="https://fonts.googleapis.com/css2?family=Balsamiq+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Bellefair&family=Outfit:wght@100..900&family=PT+Serif:ital,wght@0,400;0,700;1,400;1,700&family=Pacifico&family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">
  <title>Proyecto 5_2</title>

  <style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    .rectangulo {
        width: 704px;
        height: 847px;
        background-color: #F2F2EB;
        position: relative;
        display: grid;
        grid-template-rows: repeat(4, 1fr);
        justify-items: center;
        align-items: center;
        padding: 4rem 3rem;
    }

    body {
        width: 1596px;
        height: 1859px;
        background-color: #ffffff;
        display: flex;
        justify-content: center;
        align-items: center;
        font-family: "Outfit";
        color: #000;
    }

    .indice-item {
        display: flex;
        flex-direction: column;
        align-items: center;
        text-align: center;
        line-height: 1.3;
    }

    .numero {
        font-family: "Oswald";
        font-size: 4rem;
        font-weight: 800;
        line-height: 1;
    }

    .nombre {
        font-size: 1.6rem;
        font-weight: 600;
        margin-top: 0.3rem;
    }

    .descripcion {
        font-size: 0.9rem;
        font-weight: 400;
        color: #111;
        margin-top: 0.3rem;
        text-align: left;
    }

    .item-01 .descripcion,
    .item-03 .descripcion {
        text-align: left;
        align-self: flex-start;
    }

    .item-02 .descripcion,
    .item-04 .descripcion {
        text-align: right;
        align-self: flex-end;
    }

    .vertical-text {
        position: absolute;
        top: 50%;
        right: -2rem; /* entre el fondo y el rectangulo */
        transform: translateY(-50%) rotate(180deg);
        writing-mode: vertical-rl;
        font-family: "Purple Purse", serif;
        font-size: 2rem;
        font-weight: 800;
        letter-spacing: 0.05em;
        color: #000;
    }

    @media (max-width: 700px) {
      .vertical-text {
        font-size: 2.5rem;
        right: -3rem;
      }
      .numero {
        font-size: 3rem;
      }
      .nombre {
        font-size: 1.3rem;
      }
    }
  </style>
</head>
<body>
  <div class="rectangulo">
    <div class="indice-item item-01">
      <div class="numero">01</div>
      <div class="nombre">Mónica Angel</div>
      <div class="descripcion">
        Study for Homage to the Square,<br/>
        Terrestrial II 1960, Oil on Masonite
      </div>
    </div>

    <div class="indice-item item-02">
      <div class="numero">02</div>
      <div class="nombre">Alba Castelló</div>
      <div class="descripcion">
        Josef Albers, Blue Call<br />
        (Study for Homage to the Square), 1956
      </div>
    </div>

     <div class="indice-item item-03">
      <div class="numero">03</div>
      <div class="nombre">Alicia María</div>
      <div class="descripcion">
        Josef Albers, Homenaje al cuadrado<br/>
        Cool Rising, 1963, Oil on Masonite
      </div>
    </div>

    <div class="indice-item item-04">
      <div class="numero">04</div>
      <div class="nombre">Ignacio González</div>
      <div class="descripcion">
        Josef Albers, Homage to the Square, Ascending,<br/>
        1953, Oil on composition board
      </div>
    </div>

    <div class="vertical-text"><h2>JOSEF ALBERS</h2></div>
  </div>
</body>
</html>
