#define ArrayCount 42 //иттерации цикла вывода значений в сериал
#define ArrayCount 42
void setup() {
  // put your setup code here, to run once:
Serial.begin(9600);
}

void loop() {
  // put your main code here, to run repeatedly:

//объявление тестовых массивов
 bool Pins0[42];
 bool Pins1[42];
 bool Pins2[42];
 bool Pins3[42];
 bool Pins4[42];
 bool Pins5[42];
 bool Pins6[42];
 bool Pins7[42];
 bool Pins8[42];
 bool Pins9[42];
 bool Pins10[42];
 bool Pins11[42];
 bool Pins12[42];
 bool Pins13[42];

//эталон
 bool Calibr0[42] = {1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0};
 bool Calibr1[42] = {0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0};
 bool Calibr2[42] = {0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0};
 bool Calibr3[42] = {0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0};
 bool Calibr4[42] = {0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0};
 bool Calibr5[42] = {0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0};
 bool Calibr6[42] = {0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0};
 bool Calibr7[42] = {0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0};
 bool Calibr8[42] = {0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0};
 bool Calibr9[42] = {0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0};
 bool Calibr10[42] = {0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0};
 bool Calibr11[42] = {0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0};
 bool Calibr12[42] = {0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0};
 bool Calibr13[42] = {0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 1};
delay(1000);
//цикл 1  
 //пинмод1
   pinMode (2, OUTPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(2, HIGH);
 //запись пинов1
   Pins0[0]=digitalRead(2);
   Pins0[1]=digitalRead(3);
   Pins0[2]=digitalRead(4);
   Pins0[3]=digitalRead(5);
   Pins0[4]=digitalRead(6);
   Pins0[5]=digitalRead(7);
   Pins0[6]=digitalRead(8);
   Pins0[7]=digitalRead(9);
   Pins0[8]=digitalRead(10);
   Pins0[9]=digitalRead(11);
   Pins0[10]=digitalRead(12);
   Pins0[11]=digitalRead(13);
   Pins0[12]=digitalRead(14);
   Pins0[13]=digitalRead(15);
   Pins0[14]=digitalRead(16);
   Pins0[15]=digitalRead(17);
   Pins0[16]=digitalRead(18);
   Pins0[17]=digitalRead(19);
   Pins0[18]=digitalRead(22);
   Pins0[19]=digitalRead(23);
   Pins0[20]=digitalRead(24);
   Pins0[21]=digitalRead(25);
   Pins0[22]=digitalRead(26);
   Pins0[23]=digitalRead(27);
   Pins0[24]=digitalRead(28);
   Pins0[25]=digitalRead(29);
   Pins0[26]=digitalRead(30);
   Pins0[27]=digitalRead(31);
   Pins0[28]=digitalRead(32);
   Pins0[29]=digitalRead(33);
   Pins0[30]=digitalRead(34);
   Pins0[31]=digitalRead(35);
   Pins0[32]=digitalRead(36);
   Pins0[33]=digitalRead(37);
   Pins0[34]=digitalRead(38);
   Pins0[35]=digitalRead(39);
   Pins0[36]=digitalRead(40);
   Pins0[37]=digitalRead(41);
   Pins0[38]=digitalRead(42);
   Pins0[39]=digitalRead(43);
   Pins0[40]=digitalRead(44);
   Pins0[41]=digitalRead(45);
 
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins0[i]);

 }
 Serial.println(" -1");
 delay(100);


//цикл 2  
 //пинмод2
   pinMode (2, INPUT);
   pinMode (3, OUTPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(3, HIGH);
 //запись пинов2
   Pins1[0]=digitalRead(2);
   Pins1[1]=digitalRead(3);
   Pins1[2]=digitalRead(4);
   Pins1[3]=digitalRead(5);
   Pins1[4]=digitalRead(6);
   Pins1[5]=digitalRead(7);
   Pins1[6]=digitalRead(8);
   Pins1[7]=digitalRead(9);
   Pins1[8]=digitalRead(10);
   Pins1[9]=digitalRead(11);
   Pins1[10]=digitalRead(12);
   Pins1[11]=digitalRead(13);
   Pins1[12]=digitalRead(14);
   Pins1[13]=digitalRead(15);
   Pins1[14]=digitalRead(16);
   Pins1[15]=digitalRead(17);
   Pins1[16]=digitalRead(18);
   Pins1[17]=digitalRead(19);
   Pins1[18]=digitalRead(22);
   Pins1[19]=digitalRead(23);
   Pins1[20]=digitalRead(24);
   Pins1[21]=digitalRead(25);
   Pins1[22]=digitalRead(26);
   Pins1[23]=digitalRead(27);
   Pins1[24]=digitalRead(28);
   Pins1[25]=digitalRead(29);
   Pins1[26]=digitalRead(30);
   Pins1[27]=digitalRead(31);
   Pins1[28]=digitalRead(32);
   Pins1[29]=digitalRead(33);
   Pins1[30]=digitalRead(34);
   Pins1[31]=digitalRead(35);
   Pins1[32]=digitalRead(36);
   Pins1[33]=digitalRead(37);
   Pins1[34]=digitalRead(38);
   Pins1[35]=digitalRead(39);
   Pins1[36]=digitalRead(40);
   Pins1[37]=digitalRead(41);
   Pins1[38]=digitalRead(42);
   Pins1[39]=digitalRead(43);
   Pins1[40]=digitalRead(44);
   Pins1[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins1[i]);

 }
 Serial.println(" -2");
 delay(100);
 
//цикл 3  
 //пинмод3
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, OUTPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(4, HIGH);
 //запись пинов3
   Pins2[0]=digitalRead(2);
   Pins2[1]=digitalRead(3);
   Pins2[2]=digitalRead(4);
   Pins2[3]=digitalRead(5);
   Pins2[4]=digitalRead(6);
   Pins2[5]=digitalRead(7);
   Pins2[6]=digitalRead(8);
   Pins2[7]=digitalRead(9);
   Pins2[8]=digitalRead(10);
   Pins2[9]=digitalRead(11);
   Pins2[10]=digitalRead(12);
   Pins2[11]=digitalRead(13);
   Pins2[12]=digitalRead(14);
   Pins2[13]=digitalRead(15);
   Pins2[14]=digitalRead(16);
   Pins2[15]=digitalRead(17);
   Pins2[16]=digitalRead(18);
   Pins2[17]=digitalRead(19);
   Pins2[18]=digitalRead(22);
   Pins2[19]=digitalRead(23);
   Pins2[20]=digitalRead(24);
   Pins2[21]=digitalRead(25);
   Pins2[22]=digitalRead(26);
   Pins2[23]=digitalRead(27);
   Pins2[24]=digitalRead(28);
   Pins2[25]=digitalRead(29);
   Pins2[26]=digitalRead(30);
   Pins2[27]=digitalRead(31);
   Pins2[28]=digitalRead(32);
   Pins2[29]=digitalRead(33);
   Pins2[30]=digitalRead(34);
   Pins2[31]=digitalRead(35);
   Pins2[32]=digitalRead(36);
   Pins2[33]=digitalRead(37);
   Pins2[34]=digitalRead(38);
   Pins2[35]=digitalRead(39);
   Pins2[36]=digitalRead(40);
   Pins2[37]=digitalRead(41);
   Pins2[38]=digitalRead(42);
   Pins2[39]=digitalRead(43);
   Pins2[40]=digitalRead(44);
   Pins2[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins2[i]);

 }
 Serial.println(" -3");
 delay(100);
//цикл 4  
 //пинмод4
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, OUTPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(5, HIGH);
 //запись пинов4
   Pins3[0]=digitalRead(2);
   Pins3[1]=digitalRead(3);
   Pins3[2]=digitalRead(4);
   Pins3[3]=digitalRead(5);
   Pins3[4]=digitalRead(6);
   Pins3[5]=digitalRead(7);
   Pins3[6]=digitalRead(8);
   Pins3[7]=digitalRead(9);
   Pins3[8]=digitalRead(10);
   Pins3[9]=digitalRead(11);
   Pins3[10]=digitalRead(12);
   Pins3[11]=digitalRead(13);
   Pins3[12]=digitalRead(14);
   Pins3[13]=digitalRead(15);
   Pins3[14]=digitalRead(16);
   Pins3[15]=digitalRead(17);
   Pins3[16]=digitalRead(18);
   Pins3[17]=digitalRead(19);
   Pins3[18]=digitalRead(22);
   Pins3[19]=digitalRead(23);
   Pins3[20]=digitalRead(24);
   Pins3[21]=digitalRead(25);
   Pins3[22]=digitalRead(26);
   Pins3[23]=digitalRead(27);
   Pins3[24]=digitalRead(28);
   Pins3[25]=digitalRead(29);
   Pins3[26]=digitalRead(30);
   Pins3[27]=digitalRead(31);
   Pins3[28]=digitalRead(32);
   Pins3[29]=digitalRead(33);
   Pins3[30]=digitalRead(34);
   Pins3[31]=digitalRead(35);
   Pins3[32]=digitalRead(36);
   Pins3[33]=digitalRead(37);
   Pins3[34]=digitalRead(38);
   Pins3[35]=digitalRead(39);
   Pins3[36]=digitalRead(40);
   Pins3[37]=digitalRead(41);
   Pins3[38]=digitalRead(42);
   Pins3[39]=digitalRead(43);
   Pins3[40]=digitalRead(44);
   Pins3[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins3[i]);

 }
 Serial.println(" -4");
 delay(100);
//цикл 5  
 //пинмод5
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, OUTPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(6, HIGH);
 //запись пинов5
   Pins4[0]=digitalRead(2);
   Pins4[1]=digitalRead(3);
   Pins4[2]=digitalRead(4);
   Pins4[3]=digitalRead(5);
   Pins4[4]=digitalRead(6);
   Pins4[5]=digitalRead(7);
   Pins4[6]=digitalRead(8);
   Pins4[7]=digitalRead(9);
   Pins4[8]=digitalRead(10);
   Pins4[9]=digitalRead(11);
   Pins4[10]=digitalRead(12);
   Pins4[11]=digitalRead(13);
   Pins4[12]=digitalRead(14);
   Pins4[13]=digitalRead(15);
   Pins4[14]=digitalRead(16);
   Pins4[15]=digitalRead(17);
   Pins4[16]=digitalRead(18);
   Pins4[17]=digitalRead(19);
   Pins4[18]=digitalRead(22);
   Pins4[19]=digitalRead(23);
   Pins4[20]=digitalRead(24);
   Pins4[21]=digitalRead(25);
   Pins4[22]=digitalRead(26);
   Pins4[23]=digitalRead(27);
   Pins4[24]=digitalRead(28);
   Pins4[25]=digitalRead(29);
   Pins4[26]=digitalRead(30);
   Pins4[27]=digitalRead(31);
   Pins4[28]=digitalRead(32);
   Pins4[29]=digitalRead(33);
   Pins4[30]=digitalRead(34);
   Pins4[31]=digitalRead(35);
   Pins4[32]=digitalRead(36);
   Pins4[33]=digitalRead(37);
   Pins4[34]=digitalRead(38);
   Pins4[35]=digitalRead(39);
   Pins4[36]=digitalRead(40);
   Pins4[37]=digitalRead(41);
   Pins4[38]=digitalRead(42);
   Pins4[39]=digitalRead(43);
   Pins4[40]=digitalRead(44);
   Pins4[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins4[i]);

 }
 Serial.println(" -5");
 delay(100);
//цикл 6  
 //пинмод6
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, OUTPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(7, HIGH);
 //запись пинов6
   Pins5[0]=digitalRead(2);
   Pins5[1]=digitalRead(3);
   Pins5[2]=digitalRead(4);
   Pins5[3]=digitalRead(5);
   Pins5[4]=digitalRead(6);
   Pins5[5]=digitalRead(7);
   Pins5[6]=digitalRead(8);
   Pins5[7]=digitalRead(9);
   Pins5[8]=digitalRead(10);
   Pins5[9]=digitalRead(11);
   Pins5[10]=digitalRead(12);
   Pins5[11]=digitalRead(13);
   Pins5[12]=digitalRead(14);
   Pins5[13]=digitalRead(15);
   Pins5[14]=digitalRead(16);
   Pins5[15]=digitalRead(17);
   Pins5[16]=digitalRead(18);
   Pins5[17]=digitalRead(19);
   Pins5[18]=digitalRead(22);
   Pins5[19]=digitalRead(23);
   Pins5[20]=digitalRead(24);
   Pins5[21]=digitalRead(25);
   Pins5[22]=digitalRead(26);
   Pins5[23]=digitalRead(27);
   Pins5[24]=digitalRead(28);
   Pins5[25]=digitalRead(29);
   Pins5[26]=digitalRead(30);
   Pins5[27]=digitalRead(31);
   Pins5[28]=digitalRead(32);
   Pins5[29]=digitalRead(33);
   Pins5[30]=digitalRead(34);
   Pins5[31]=digitalRead(35);
   Pins5[32]=digitalRead(36);
   Pins5[33]=digitalRead(37);
   Pins5[34]=digitalRead(38);
   Pins5[35]=digitalRead(39);
   Pins5[36]=digitalRead(40);
   Pins5[37]=digitalRead(41);
   Pins5[38]=digitalRead(42);
   Pins5[39]=digitalRead(43);
   Pins5[40]=digitalRead(44);
   Pins5[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins5[i]);

 }
 Serial.println(" -6");
 delay(100);
//цикл 7
 //пинмод7
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, OUTPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(8, HIGH);
 //запись пинов7
   Pins6[0]=digitalRead(2);
   Pins6[1]=digitalRead(3);
   Pins6[2]=digitalRead(4);
   Pins6[3]=digitalRead(5);
   Pins6[4]=digitalRead(6);
   Pins6[5]=digitalRead(7);
   Pins6[6]=digitalRead(8);
   Pins6[7]=digitalRead(9);
   Pins6[8]=digitalRead(10);
   Pins6[9]=digitalRead(11);
   Pins6[10]=digitalRead(12);
   Pins6[11]=digitalRead(13);
   Pins6[12]=digitalRead(14);
   Pins6[13]=digitalRead(15);
   Pins6[14]=digitalRead(16);
   Pins6[15]=digitalRead(17);
   Pins6[16]=digitalRead(18);
   Pins6[17]=digitalRead(19);
   Pins6[18]=digitalRead(22);
   Pins6[19]=digitalRead(23);
   Pins6[20]=digitalRead(24);
   Pins6[21]=digitalRead(25);
   Pins6[22]=digitalRead(26);
   Pins6[23]=digitalRead(27);
   Pins6[24]=digitalRead(28);
   Pins6[25]=digitalRead(29);
   Pins6[26]=digitalRead(30);
   Pins6[27]=digitalRead(31);
   Pins6[28]=digitalRead(32);
   Pins6[29]=digitalRead(33);
   Pins6[30]=digitalRead(34);
   Pins6[31]=digitalRead(35);
   Pins6[32]=digitalRead(36);
   Pins6[33]=digitalRead(37);
   Pins6[34]=digitalRead(38);
   Pins6[35]=digitalRead(39);
   Pins6[36]=digitalRead(40);
   Pins6[37]=digitalRead(41);
   Pins6[38]=digitalRead(42);
   Pins6[39]=digitalRead(43);
   Pins6[40]=digitalRead(44);
   Pins6[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins6[i]);

 }
 Serial.println(" -7");
 delay(100);
//цикл 8  
 //пинмод1
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, OUTPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(9, HIGH);
 //запись пинов8
   Pins7[0]=digitalRead(2);
   Pins7[1]=digitalRead(3);
   Pins7[2]=digitalRead(4);
   Pins7[3]=digitalRead(5);
   Pins7[4]=digitalRead(6);
   Pins7[5]=digitalRead(7);
   Pins7[6]=digitalRead(8);
   Pins7[7]=digitalRead(9);
   Pins7[8]=digitalRead(10);
   Pins7[9]=digitalRead(11);
   Pins7[10]=digitalRead(12);
   Pins7[11]=digitalRead(13);
   Pins7[12]=digitalRead(14);
   Pins7[13]=digitalRead(15);
   Pins7[14]=digitalRead(16);
   Pins7[15]=digitalRead(17);
   Pins7[16]=digitalRead(18);
   Pins7[17]=digitalRead(19);
   Pins7[18]=digitalRead(22);
   Pins7[19]=digitalRead(23);
   Pins7[20]=digitalRead(24);
   Pins7[21]=digitalRead(25);
   Pins7[22]=digitalRead(26);
   Pins7[23]=digitalRead(27);
   Pins7[24]=digitalRead(28);
   Pins7[25]=digitalRead(29);
   Pins7[26]=digitalRead(30);
   Pins7[27]=digitalRead(31);
   Pins7[28]=digitalRead(32);
   Pins7[29]=digitalRead(33);
   Pins7[30]=digitalRead(34);
   Pins7[31]=digitalRead(35);
   Pins7[32]=digitalRead(36);
   Pins7[33]=digitalRead(37);
   Pins7[34]=digitalRead(38);
   Pins7[35]=digitalRead(39);
   Pins7[36]=digitalRead(40);
   Pins7[37]=digitalRead(41);
   Pins7[38]=digitalRead(42);
   Pins7[39]=digitalRead(43);
   Pins7[40]=digitalRead(44);
   Pins7[41]=digitalRead(45);
 
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins7[i]);

 }
 Serial.println(" -8");
 delay(100);


//цикл 9
 //пинмод9
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, OUTPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(10, HIGH);
 //запись пинов9
   Pins8[0]=digitalRead(2);
   Pins8[1]=digitalRead(3);
   Pins8[2]=digitalRead(4);
   Pins8[3]=digitalRead(5);
   Pins8[4]=digitalRead(6);
   Pins8[5]=digitalRead(7);
   Pins8[6]=digitalRead(8);
   Pins8[7]=digitalRead(9);
   Pins8[8]=digitalRead(10);
   Pins8[9]=digitalRead(11);
   Pins8[10]=digitalRead(12);
   Pins8[11]=digitalRead(13);
   Pins8[12]=digitalRead(14);
   Pins8[13]=digitalRead(15);
   Pins8[14]=digitalRead(16);
   Pins8[15]=digitalRead(17);
   Pins8[16]=digitalRead(18);
   Pins8[17]=digitalRead(19);
   Pins8[18]=digitalRead(22);
   Pins8[19]=digitalRead(23);
   Pins8[20]=digitalRead(24);
   Pins8[21]=digitalRead(25);
   Pins8[22]=digitalRead(26);
   Pins8[23]=digitalRead(27);
   Pins8[24]=digitalRead(28);
   Pins8[25]=digitalRead(29);
   Pins8[26]=digitalRead(30);
   Pins8[27]=digitalRead(31);
   Pins8[28]=digitalRead(32);
   Pins8[29]=digitalRead(33);
   Pins8[30]=digitalRead(34);
   Pins8[31]=digitalRead(35);
   Pins8[32]=digitalRead(36);
   Pins8[33]=digitalRead(37);
   Pins8[34]=digitalRead(38);
   Pins8[35]=digitalRead(39);
   Pins8[36]=digitalRead(40);
   Pins8[37]=digitalRead(41);
   Pins8[38]=digitalRead(42);
   Pins8[39]=digitalRead(43);
   Pins8[40]=digitalRead(44);
   Pins8[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins8[i]);

 }
 Serial.println(" -9");
 delay(100);
 
//цикл 10  
 //пинмод10
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, OUTPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(11, HIGH);
 //запись пинов10
   Pins9[0]=digitalRead(2);
   Pins9[1]=digitalRead(3);
   Pins9[2]=digitalRead(4);
   Pins9[3]=digitalRead(5);
   Pins9[4]=digitalRead(6);
   Pins9[5]=digitalRead(7);
   Pins9[6]=digitalRead(8);
   Pins9[7]=digitalRead(9);
   Pins9[8]=digitalRead(10);
   Pins9[9]=digitalRead(11);
   Pins9[10]=digitalRead(12);
   Pins9[11]=digitalRead(13);
   Pins9[12]=digitalRead(14);
   Pins9[13]=digitalRead(15);
   Pins9[14]=digitalRead(16);
   Pins9[15]=digitalRead(17);
   Pins9[16]=digitalRead(18);
   Pins9[17]=digitalRead(19);
   Pins9[18]=digitalRead(22);
   Pins9[19]=digitalRead(23);
   Pins9[20]=digitalRead(24);
   Pins9[21]=digitalRead(25);
   Pins9[22]=digitalRead(26);
   Pins9[23]=digitalRead(27);
   Pins9[24]=digitalRead(28);
   Pins9[25]=digitalRead(29);
   Pins9[26]=digitalRead(30);
   Pins9[27]=digitalRead(31);
   Pins9[28]=digitalRead(32);
   Pins9[29]=digitalRead(33);
   Pins9[30]=digitalRead(34);
   Pins9[31]=digitalRead(35);
   Pins9[32]=digitalRead(36);
   Pins9[33]=digitalRead(37);
   Pins9[34]=digitalRead(38);
   Pins9[35]=digitalRead(39);
   Pins9[36]=digitalRead(40);
   Pins9[37]=digitalRead(41);
   Pins9[38]=digitalRead(42);
   Pins9[39]=digitalRead(43);
   Pins9[40]=digitalRead(44);
   Pins9[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins9[i]);

 }
 Serial.println(" -10");
 delay(100);
//цикл 11
 //пинмод11
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, OUTPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(12, HIGH);
 //запись пинов11
   Pins10[0]=digitalRead(2);
   Pins10[1]=digitalRead(3);
   Pins10[2]=digitalRead(4);
   Pins10[3]=digitalRead(5);
   Pins10[4]=digitalRead(6);
   Pins10[5]=digitalRead(7);
   Pins10[6]=digitalRead(8);
   Pins10[7]=digitalRead(9);
   Pins10[8]=digitalRead(10);
   Pins10[9]=digitalRead(11);
   Pins10[10]=digitalRead(12);
   Pins10[11]=digitalRead(13);
   Pins10[12]=digitalRead(14);
   Pins10[13]=digitalRead(15);
   Pins10[14]=digitalRead(16);
   Pins10[15]=digitalRead(17);
   Pins10[16]=digitalRead(18);
   Pins10[17]=digitalRead(19);
   Pins10[18]=digitalRead(22);
   Pins10[19]=digitalRead(23);
   Pins10[20]=digitalRead(24);
   Pins10[21]=digitalRead(25);
   Pins10[22]=digitalRead(26);
   Pins10[23]=digitalRead(27);
   Pins10[24]=digitalRead(28);
   Pins10[25]=digitalRead(29);
   Pins10[26]=digitalRead(30);
   Pins10[27]=digitalRead(31);
   Pins10[28]=digitalRead(32);
   Pins10[29]=digitalRead(33);
   Pins10[30]=digitalRead(34);
   Pins10[31]=digitalRead(35);
   Pins10[32]=digitalRead(36);
   Pins10[33]=digitalRead(37);
   Pins10[34]=digitalRead(38);
   Pins10[35]=digitalRead(39);
   Pins10[36]=digitalRead(40);
   Pins10[37]=digitalRead(41);
   Pins10[38]=digitalRead(42);
   Pins10[39]=digitalRead(43);
   Pins10[40]=digitalRead(44);
   Pins10[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins10[i]);

 }
 Serial.println(" -11");
 delay(100);
//цикл 12 
 //пинмод12
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, OUTPUT);
   pinMode (14, INPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(13, HIGH);
 //запись пинов12
   Pins11[0]=digitalRead(2);
   Pins11[1]=digitalRead(3);
   Pins11[2]=digitalRead(4);
   Pins11[3]=digitalRead(5);
   Pins11[4]=digitalRead(6);
   Pins11[5]=digitalRead(7);
   Pins11[6]=digitalRead(8);
   Pins11[7]=digitalRead(9);
   Pins11[8]=digitalRead(10);
   Pins11[9]=digitalRead(11);
   Pins11[10]=digitalRead(12);
   Pins11[11]=digitalRead(13);
   Pins11[12]=digitalRead(14);
   Pins11[13]=digitalRead(15);
   Pins11[14]=digitalRead(16);
   Pins11[15]=digitalRead(17);
   Pins11[16]=digitalRead(18);
   Pins11[17]=digitalRead(19);
   Pins11[18]=digitalRead(22);
   Pins11[19]=digitalRead(23);
   Pins11[20]=digitalRead(24);
   Pins11[21]=digitalRead(25);
   Pins11[22]=digitalRead(26);
   Pins11[23]=digitalRead(27);
   Pins11[24]=digitalRead(28);
   Pins11[25]=digitalRead(29);
   Pins11[26]=digitalRead(30);
   Pins11[27]=digitalRead(31);
   Pins11[28]=digitalRead(32);
   Pins11[29]=digitalRead(33);
   Pins11[30]=digitalRead(34);
   Pins11[31]=digitalRead(35);
   Pins11[32]=digitalRead(36);
   Pins11[33]=digitalRead(37);
   Pins11[34]=digitalRead(38);
   Pins11[35]=digitalRead(39);
   Pins11[36]=digitalRead(40);
   Pins11[37]=digitalRead(41);
   Pins11[38]=digitalRead(42);
   Pins11[39]=digitalRead(43);
   Pins11[40]=digitalRead(44);
   Pins11[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins11[i]);

 }
 Serial.println(" -12");
 delay(100);
//цикл 13  
 //пинмод13
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, OUTPUT);
   pinMode (15, INPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(14, HIGH);
 //запись пинов13
   Pins12[0]=digitalRead(2);
   Pins12[1]=digitalRead(3);
   Pins12[2]=digitalRead(4);
   Pins12[3]=digitalRead(5);
   Pins12[4]=digitalRead(6);
   Pins12[5]=digitalRead(7);
   Pins12[6]=digitalRead(8);
   Pins12[7]=digitalRead(9);
   Pins12[8]=digitalRead(10);
   Pins12[9]=digitalRead(11);
   Pins12[10]=digitalRead(12);
   Pins12[11]=digitalRead(13);
   Pins12[12]=digitalRead(14);
   Pins12[13]=digitalRead(15);
   Pins12[14]=digitalRead(16);
   Pins12[15]=digitalRead(17);
   Pins12[16]=digitalRead(18);
   Pins12[17]=digitalRead(19);
   Pins12[18]=digitalRead(22);
   Pins12[19]=digitalRead(23);
   Pins12[20]=digitalRead(24);
   Pins12[21]=digitalRead(25);
   Pins12[22]=digitalRead(26);
   Pins12[23]=digitalRead(27);
   Pins12[24]=digitalRead(28);
   Pins12[25]=digitalRead(29);
   Pins12[26]=digitalRead(30);
   Pins12[27]=digitalRead(31);
   Pins12[28]=digitalRead(32);
   Pins12[29]=digitalRead(33);
   Pins12[30]=digitalRead(34);
   Pins12[31]=digitalRead(35);
   Pins12[32]=digitalRead(36);
   Pins12[33]=digitalRead(37);
   Pins12[34]=digitalRead(38);
   Pins12[35]=digitalRead(39);
   Pins12[36]=digitalRead(40);
   Pins12[37]=digitalRead(41);
   Pins12[38]=digitalRead(42);
   Pins12[39]=digitalRead(43);
   Pins12[40]=digitalRead(44);
   Pins12[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins12[i]);

 }
 Serial.println(" -13");
 delay(100);
//цикл 14
 //пинмод14
   pinMode (2, INPUT);
   pinMode (3, INPUT);
   pinMode (4, INPUT);
   pinMode (5, INPUT);
   pinMode (6, INPUT);
   pinMode (7, INPUT);
   pinMode (8, INPUT);
   pinMode (9, INPUT);
   pinMode (10, INPUT);
   pinMode (11, INPUT);
   pinMode (12, INPUT);
   pinMode (13, INPUT);
   pinMode (14, INPUT);
   pinMode (15, OUTPUT);
   pinMode (16, INPUT);
   pinMode (17, INPUT);
   pinMode (18, INPUT);
   pinMode (19, INPUT);
   pinMode (22, INPUT);
   pinMode (23, INPUT);
   pinMode (24, INPUT);
   pinMode (25, INPUT);
   pinMode (26, INPUT);
   pinMode (27, INPUT);
   pinMode (28, INPUT);
   pinMode (29, INPUT);
   pinMode (30, INPUT);
   pinMode (31, INPUT);
   pinMode (32, INPUT);
   pinMode (33, INPUT);
   pinMode (34, INPUT);
   pinMode (35, INPUT);
   pinMode (36, INPUT);
   pinMode (37, INPUT);
   pinMode (38, INPUT);
   pinMode (39, INPUT);
   pinMode (40, INPUT);
   pinMode (41, INPUT);
   pinMode (42, INPUT);
   pinMode (43, INPUT);
   pinMode (44, INPUT);
   pinMode (45, INPUT);
   digitalWrite(15, HIGH);
 //запись пинов14
   Pins13[0]=digitalRead(2);
   Pins13[1]=digitalRead(3);
   Pins13[2]=digitalRead(4);
   Pins13[3]=digitalRead(5);
   Pins13[4]=digitalRead(6);
   Pins13[5]=digitalRead(7);
   Pins13[6]=digitalRead(8);
   Pins13[7]=digitalRead(9);
   Pins13[8]=digitalRead(10);
   Pins13[9]=digitalRead(11);
   Pins13[10]=digitalRead(12);
   Pins13[11]=digitalRead(13);
   Pins13[12]=digitalRead(14);
   Pins13[13]=digitalRead(15);
   Pins13[14]=digitalRead(16);
   Pins13[15]=digitalRead(17);
   Pins13[16]=digitalRead(18);
   Pins13[17]=digitalRead(19);
   Pins13[18]=digitalRead(22);
   Pins13[19]=digitalRead(23);
   Pins13[20]=digitalRead(24);
   Pins13[21]=digitalRead(25);
   Pins13[22]=digitalRead(26);
   Pins13[23]=digitalRead(27);
   Pins13[24]=digitalRead(28);
   Pins13[25]=digitalRead(29);
   Pins13[26]=digitalRead(30);
   Pins13[27]=digitalRead(31);
   Pins13[28]=digitalRead(32);
   Pins13[29]=digitalRead(33);
   Pins13[30]=digitalRead(34);
   Pins13[31]=digitalRead(35);
   Pins13[32]=digitalRead(36);
   Pins13[33]=digitalRead(37);
   Pins13[34]=digitalRead(38);
   Pins13[35]=digitalRead(39);
   Pins13[36]=digitalRead(40);
   Pins13[37]=digitalRead(41);
   Pins13[38]=digitalRead(42);
   Pins13[39]=digitalRead(43);
   Pins13[40]=digitalRead(44);
   Pins13[41]=digitalRead(45);
  
  for(int i = 0; i<ArrayCount; i++) {
 Serial.print(Pins13[i]);

 }
 Serial.println(" -14");
 delay(100);
//Сравнение с эталоном
 int Flag;
 Flag=0;
 // Сравнение 1
   for(int i = 0; i<ArrayCount; i++){
   if(Pins0[i]==Calibr0[i]){
   Flag++;
   } 
   }   
 // Сравнение 2 
   for(int i = 0; i<ArrayCount; i++){
   if(Pins1[i]==Calibr1[i]){
   Flag++;
   }
   }
 // Сравнение 3
   for(int i = 0; i<ArrayCount; i++){
   if(Pins2[i]==Calibr2[i]){
   Flag++;
   } 
   }
 // Сравнение 4
   for(int i = 0; i<ArrayCount; i++){
   if(Pins3[i]==Calibr3[i]){
   Flag++;
   } 
   }   
 // Сравнение 5
    for(int i = 0; i<ArrayCount; i++){
   if(Pins4[i]==Calibr4[i]){
   Flag++;
   } 
   }
   // Сравнение 6
     for(int i = 0; i<ArrayCount; i++){
     if(Pins5[i]==Calibr5[i]){
     Flag++;
    } 
    }
 // Сравнение 7
    for(int i = 0; i<ArrayCount; i++){
   if(Pins6[i]==Calibr6[i]){
   Flag++;
   } 
   }
 // Сравнение 8
   for(int i = 0; i<ArrayCount; i++){
   if(Pins7[i]==Calibr7[i]){
   Flag++;
   } 
   }   
 // Сравнение 9
    for(int i = 0; i<ArrayCount; i++){
   if(Pins8[i]==Calibr8[i]){
   Flag++;
   } 
   }   
 // Сравнение 10 
    for(int i = 0; i<ArrayCount; i++){
   if(Pins9[i]==Calibr9[i]){
   Flag++;
   } 
   }   
 // Сравнение 11
    for(int i = 0; i<ArrayCount; i++){
   if(Pins10[i]==Calibr10[i]){
   Flag++;
   }
   } 
 // Сравнение 12
    for(int i = 0; i<ArrayCount; i++){
   if(Pins11[i]==Calibr11[i]){
   Flag++;
   } 
   }
 // Сравнение 13
   for(int i = 0; i<ArrayCount; i++){
   if(Pins12[i]==Calibr12[i]){
   Flag++;
   }  
   }
 // Сравнение 14 
    for(int i = 0; i<ArrayCount; i++){
   if(Pins13[i]==Calibr13[i]){
   Flag++;
   } 
   }   
 Serial.println(Flag);
 if(Flag==14){
 Serial.println("Good Job");
 }
 else{
  
 Serial.println("HEROTA, PEREDELAY");
 }
 delay(2000);

}
