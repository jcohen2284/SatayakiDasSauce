# Module 2: Data & Modeling
%ENGE1215 Mon/Wed 11:15 10/16/18
%Code for ENGE 1215: SustainingKnocksonOurKnees
%Purpose Statement: Analyize USGS Water Use Data
clc
clear
 load('WaterUseData(3)')
while input('Type 0 twice to end Program, Or, Press any other key') ~= 0
infoButtons = input('Press a key 1-15 twice to view different graphs');
if infoButtons == 1
 plot(Year,AquacultureinBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 2
 plot(Year,CommercialinBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 3
 plot(Year,IrrigationinBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 4
 plot(Year,LivestockinBgald) 
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 5
 plot(Year,Populationinmillions) 
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 6
 plot(Year,MiningInBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 7
 plot(Year,PublicsupplyinBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 8
 plot(Year,SelfsupplieddomesticinBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 9
 plot(Year,SelfsuppliedindustrialinBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 10
 plot(Year,ThermoelectricpowerinBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 11
  plot(Year,TotalGroundwaterfreshinBgald) 
 figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 12
 plot(Year,TotalGroundwatersalineinBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 13
 plot(Year,TotalSurfacewaterfreshinBgald) 
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 14
 plot(Year,TotalSurfacewatersalineinBgald)
 figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end

if infoButtons == 15
plot(Year,TotalwithdrawalsinBgald)
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')
end
end












 
 
 
 
 





 
 
 
 
 
 








 
 
 
 
 
