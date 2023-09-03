# ESP32-wireless-game-console-MESH-network
Play 10 multiplayer (2 people) games without WiFi network.

Easy to build.

Economically responsible (the bank account will not notice).

Hours of fun

Play :

Tic-Tac-Toe
https://en.wikipedia.org/wiki/Tic-tac-toe

Vier op een rij (Four in a row)
The name says it all.

Juiste volgorde (Correct sequence)
Repeat the colors shown.

Connect 4
https://en.wikipedia.org/wiki/Connect_Four

Mastermind
https://en.wikipedia.org/wiki/Mastermind_(board_game)

Pentago
https://en.wikipedia.org/wiki/Pentago

Super Tic Tac Toe
https://en.wikipedia.org/wiki/Ultimate_tic-tac-toe

Zeeslag (Battleship)
https://en.wikipedia.org/wiki/Battleship_(game)

Smileys 11x11 (minesweeper without mines)
https://en.wikipedia.org/wiki/Microsoft_Minesweeper

Othello (beginner / pro)
https://en.wikipedia.org/wiki/Reversi


Components

2x ESP32 WROOM Devkit module

2x 4.0 TFT SPI 480X320 TFT TOUCH SCREEN

2x 5V battery

Connections

ESP32

ESP32  	5V				>>		+5V batterij
GND(3x)					>>		GND batterij
ESP32		EN(Reset)			>>		TFT RESET
ESP32		2				>>		TFT DC
ESP32		4				>> 		T_CS
ESP32		12				>>		TFT SDO(MISO)
								T_DO
ESP32		13				>>		TFT SDI(MOSI)
								T_DIN
ESP32		14				>>		TFT_SCK
								T_CLK
ESP32		15				>>		TFT CS
ESP32		25				>>		T_IRQ
ESP32		3.3V				>>		TFT LED


LCD screen

VCC						>>		+5V batterij	(J1 boven U1 NIET sluiten)
GND						>>		GND batterij
CS						>>		ESP32		15
RESET					>>		ESP32 	EN
DC						>>		ESP32		2
SDI(MOSI)					>>		ESP32		13
SCK						>>		ESP32		14
LED						>>		ESP32		+3.3V
SDO(MISO)					>>		ESP32		12
T_CLK					>>		ESP32		14
T_CS						>>		ESP32		15
T_DIN						>>		ESP32		13
T_DO						>>		ESP32		12
T_IRQ						>>		ESP32		25














