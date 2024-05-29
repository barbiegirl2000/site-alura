index

<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AluraBooks</title>
    <link rel="stylesheet" href="reset.css">
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <header class="cabeçalho">
        <div class="container">
        <span class="cabeçalho__menu-hamburguer"></span>
        <img src="/tmp/guest-8omrp0/Downloads/AluraBooks/Logo.png" alt="Logo da AluraBooks">
       </div>
       <div class="container">
       <a href="#"><img src="/tmp/guest-8omrp0/Downloads/AluraBooks/Favoritos-1.svg" alt="meus-favoritos"></a>
        <a href="#"><img src="/tmp/guest-8omrp0/Downloads/AluraBooks/Sacola.png" alt= "sacola"></a>
        <a href="#"><img src="/tmp/guest-8omrp0/Downloads/AluraBooks/Usuario.png" alt="meu-perfil"></a>
   </div>
    </header>
</body>


</html>


RESET
html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline;
}

/* HTML5 display-role reset for older browsers */
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
menu,
nav,
section {
    display: block;
}

body {
    line-height: 1;
}

ol,
ul {
    list-style: none;
}

blockquote,
q {
    quotes: none;
}

blockquote:before,
blockquote:after,
q:before,
q:after {
    content: '';
    content: none;
}

table {
    border-collapse: collapse;
    border-spacing: 0;
}


STYLE
@import url("styles/header.css");

:root {
    --cor-de-fundo: #EBECEE;
    --branco: #FFFFFF;
}


body {
    background-color: var(--cor-de-fundo);
}

h1 {
    background-color: white;
}


HEADER
cabeçalho_menu-hamburguer {
    width: 24px;
    height: 24px;
    display: inline-block;
    background-image: url("../img/Menu.svg");
    background-repeat: no-repeat;
    background-position: center;
}

.cabeçalho {
    background-color: var(--branco);
}
