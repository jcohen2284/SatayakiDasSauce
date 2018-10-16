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
xlabel('Year')
ylabel('Amount in Bgal/D or Millions')
title('Amount of Water Used per year')

infoButtons = input('Press a key 1-15 to view different graphs')
if
    infoButtons = 1
end
if
    infoButtons = 2
end
if
    infoButtons = 3
end
if
    infoButtons = 4
end
if
    infoButtons = 5
end
if
    infoButtons = 6
end
if
    infoButtons = 7
end
if
    infoButtons = 8
end
if
    infoButtons = 9
end
if
    infoButtons = 10
end
if
    infoButtons = 11
end
if
    infoButtons = 12
end
if
    infoButtons = 13
end
if
    infoButtons = 14
end
if
    infoButtons = 15
end
plot(AquacultureinBgald,Year)
plot( CommercialinBgald,Year)
plot(IrrigationinBgald,Year)
plot( LivestockinBgald,Year) ​ 
plot( MiningInBgald,Year)
plot(Populationinmillions,Year) 
plot(PublicsupplyinBgald,Year)​
plot(SelfsupplieddomesticinBgald​,Year)
plot(SelfsuppliedindustrialinBgald,Year) ​
plot(ThermoelectricpowerinBgald,Year)
plot(TotalGroundwaterfreshinBgald,Year) 
plot(TotalGroundwatersalineinBgald​,Year)
plot(TotalSurfacewaterfreshinBgald,Year) 
plot(TotalSurfacewatersalineinBgald,Year)  
plot(TotalwithdrawalsinBgald,Year) 
 
 
 
 
 
 
