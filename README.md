# Module 2: Data & Modeling
%ENGE1215 Mon/Wed 11:15 10/16/18
%Code for ENGE 1215: SustainingKnocksonOurKnees
%Purpose Statement: Analyize USGS Water Use Data
clc
clear
load('WaterUseData(3)')
figure(1)
grid
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')

infoButtons = input('Press a key 1-15 to view different graphs')
if infoButtons = 1
 plot(AquacultureinBgald,Year)
end

if infoButtons = 2
 plot( CommercialinBgald,Year)
end

if infoButtons = 3
 plot(IrrigationinBgald,Year)
end

if infoButtons = 4
 plot( LivestockinBgald,Year) ​ 
end

if infoButtons = 5
 plot(Populationinmillions,Year) 
end

if infoButtons = 6
 plot( MiningInBgald,Year)​
end

if infoButtons = 7
 plot(PublicsupplyinBgald,Year)
end

if infoButtons = 8
 plot(SelfsupplieddomesticinBgald​,Year)
end

if infoButtons = 9
 plot(SelfsuppliedindustrialinBgald,Year) ​
end

if infoButtons = 10
 plot(ThermoelectricpowerinBgald,Year)
end

if infoButtons = 11
  plot(TotalGroundwaterfreshinBgald,Year) 
end

if infoButtons = 12
 plot(TotalGroundwatersalineinBgald​,Year)
end

if infoButtons = 13
 plot(TotalSurfacewaterfreshinBgald,Year) 
end

if infoButtons = 14
 plot(TotalSurfacewatersalineinBgald,Year)
end

if infoButtons = 15
plot(TotalwithdrawalsinBgald,Year)
end













 
 
 
 
 
