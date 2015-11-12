# smartLighting
issue 0001: amberCenterLamda = 
  Nearest[amberSpd[[All, 2]] -> amberSpd[[All, 1]], 
     1] ;     using 1 to repalce maxAmberSpd (or other color leds)

  amberHwList = 
    Nearest[amberSpd[[All, 2]] -> amberSpd[[All, 1]], 0.5, 2];   using 0.5 to replace maxAmberSpd/2  (or other color leds)
