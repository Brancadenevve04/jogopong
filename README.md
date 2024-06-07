
The p5.js Editor uses cookies. Some are essential to the website functionality and allow you to manage an account and preferences. Others are not essential—they are used for analytics and allow us to learn more about our community. We never sell this data or use it for advertising. You can decide which cookies you would like to allow, and learn more in our Privacy Policy.


Allow All

Allow Essential
File
Edit
Sketch
Help
English
Log in
or
Sign up



Auto-refresh

Projeto final - Jogo Pong
by EstudanteAlura



sketch.js
104
    }
105
}
106
​
107
​
108
function incluiPlacar(){
109
  stroke(255)
110
    textAlign(CENTER);
111
    textSize(16);
112
    fill(color(255,140, 0));
113
    rect(150, 10, 40, 20);
114
    fill(255);
115
    text(meusPontos, 170, 26);
116
    fill(color(255,140, 0));
117
    rect(450, 10, 40, 20);
118
    fill(255);
119
    text(pontosDoOponente, 470, 26);
120
​
121
​
122
​
123
}
124
​
125
​
126
function marcaPonto() {
127
    if (xBolinha > 590) {
128
        meusPontos += 1;
129
        ponto.play();
130
    }
131
    if (xBolinha < 10) {
132
        pontosDoOponente += 1;
133
        ponto.play();
134
    }
135
}
136
​
137
​
138
function preload(){
139
  trilha = loadSound("trilha.mp3");
140
  ponto = loadSound("ponto.mp3");
141
  raquetada = loadSound("raquetada.mp3");
142
}
143
​
144
​
# jogo.pong
Aula Alura 
