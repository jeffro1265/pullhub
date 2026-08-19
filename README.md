Basic instructions:  

**SETUP:**  
1) Go here to access the controller webpage: https://jeffro1265.github.io/pullhub/control.html  
2) Set a unique key and press submit. It doesn't have to be complicated, just something unique so someone doesn't output to your overlay.  
3) Press **Copy Output URL** and paste that as a 1920X1080 browser source in OBS or an encoder like a Yolobox or Magewell director.  
4) Input event details and or announcer info. These are generic enough that you can use them for anything, but the first box for each will be a header with larger text.   
5) Input the participants. The recommended method of importing participants is by using a tab separated block of cells from a spreadsheet. Your spread sheet should include at least the following columns in order from left to right:   team/vehicle, driver name, city. Neither of these fields are required, but any columns not desired should at least include an empty cell for them. Hit parse to bring them down into the overlays list.   
  -If you want to enter participants in manually, you have that option as well. The class dialogue option should be skipped at this time.  
  
**USING**  
1) Press the switch beside each participant to enable the lower third overlay. The overlay will show for 10 seconds, with a countdown bar visible in the control panel. you may kill the overlay at any time by pressing the switch again. If a distance is not entered, then it will show nothing.   
  -The intended use case is to enable the overlay as driver is backing up to the sled. It will time out after 10 seconds. Once driver is finished, enter the distance and press the switch again to show the overlay with name/distance etc for 10 seconds.  
2) When all participants have finished, it will compile them into the results overlay at the bottom. The top 5 distances will be included. Select the class header from the drop down and press the show overlay switch to show the results on the overlay.  
  -There is a window that will pop-up asking to confirm the class header. This is to prevent accidentally showing the wrong class header.   
  -If you do not wish to use the distance boxes in the participants list, you can paste a block of tab separated cells (TSV) that include distances, team/vehicle, and driver name. Press the override button over-ride any distances values that were manually entered above.   
