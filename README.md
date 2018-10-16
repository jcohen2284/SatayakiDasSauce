# Module 2: Data & Modeling
%ENGE1215 Mon/Wed 11:15 10/16/18
%Code for ENGE 1215: SustainingKnocksonOurKnees
%Purpose Statement: Analyize USGS Water Use Data
clc
clear
load('WaterUseData(3)')
figure(1)
plot(Year, Amount)
grid
xlabel('Year, ppm')
ylabel('Amount,C')
title('Amount of Water USed per year')
hold on

P = polyfit(Year,Amount,1)
F = polyval(P, Year)
plot(Year,F)
