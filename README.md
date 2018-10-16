# Module 2: Data & Modeling
Code for ENGE 1215: SustainingKnocksonOurKnees
clc
clear
load('CommutingMethods(3)')
figure(1)
plot(CO2, Temp)
grid
xlabel('CO2, ppm')
ylabel('Temperature,C')
title('CO2 affecting the Temperature')
hold on

P = polyfit(CO2,Temp,1)
F = polyval(P, CO2)
plot(CO2,F)
