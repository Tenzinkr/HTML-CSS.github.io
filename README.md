<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Module 2 Solution</title>
 <style type="text/css">
   body {
  margin: 0;
  font-family: Arial, sans-serif;
}

header {
  background-color: white;
  color: black;
  padding: 20px;
  text-align: center;
}

main {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  padding: 20px;
}

.section {
  width: 30%;
  background-color:lightgrey;
  border: 1px solid #000;
  margin-bottom: 20px;
  padding: 20px;
  box-sizing: border-box;
  position: relative;
}

.section h2 {
  position: absolute;
  top: 0px;
  right: 0px;
  background-color:skyblue;
  color: black;
  padding: 2px 10px;
  margin: 0;
  border: 1px solid #000;
}


@media screen and (max-width: 991px) {
  .section {
    width: 45%;
  }
}

@media screen and (max-width: 767px) {
  .section {
    width: 100%;
  }
}

 </style>

</head>
<body>
  <header>
    <h1>Our Menu</h1>
  </header>
  <main>
    <section class="section">
      <h2 id="p1">Chicken</h2>
      <p>Chickens are relatively large birds, active by day. The body is round, the legs are unfeathered, and the wings are short. Wild junglefowl can fly; chickens and their flight muscles are too heavy to allow them to fly more than a short distance. Size and coloration vary widely between breeds. Adult chickens of both sexes have a fleshy crest on their heads called a comb or cockscomb, and hanging flaps of skin on either side under their beaks called wattles; combs and wattles are more prominent in males. Some breeds have a mutation that causes extra feathering under the face, giving the appearance of a beard.[19]</p>
    </section>
    <section class="section">
      <h2  id="p2">Beef</h2>
      <p>Beef is the culinary name for meat from cattle (Bos taurus). Beef can be prepared in various ways; cuts are often used for steak, which can be cooked to varying degrees of doneness, while trimmings are often ground or minced, as found in most hamburgers. Beef contains protein, iron, and vitamin B12. Along with other kinds of red meat, high consumption is associated with an increased risk of colorectal cancer and coronary heart disease, especially when processed. Beef has a high environmental impact, being a primary driver of deforestation with the highest greenhouse gas emissions of any agricultural product.</p>
    </section>
    <section class="section">
      <h2  id="p3">Sushi</h2>
      <p>Sushi (すし, 寿司, 鮨, 鮓, pronounced [sɯɕiꜜ] or [sɯꜜɕi] ⓘ) is a Japanese dish of prepared vinegared rice (鮨飯, sushi-meshi), usually with some sugar and salt, plus a variety of ingredients (ねた, neta), such as vegetables, and any meat, but most commonly seafood (often raw but can be cooked). Styles of sushi and its presentation vary widely, but the one key ingredient is "sushi rice", also referred to as shari (しゃり), or sumeshi (酢飯).</p>
    </section>
  </main>
</body>
</html>
