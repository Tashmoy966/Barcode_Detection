# Barcode_Detection
To perform barcode detection and decoding in python.

**Input details**
  1. An image containing multiple grocery items, with a background of single color.
  2. For some items, the barcode will be visible, and for others, it might not be visible.
  3. Some of the items might be repeated.
 
**Output details / Features**

  1.Input Image
  
   ![Screenshot from 2023-02-06 21-27-03](https://user-images.githubusercontent.com/87931949/217548498-2fc137ea-1418-4eed-b701-41bb66b25e6a.png)

  2. Creating Bounding box of blue color on the input image, around all the barcodes which are correctly read.
  
   ![Screenshot from 2023-02-08 19-23-10](https://user-images.githubusercontent.com/87931949/217549352-35f8a4f7-0ef8-4d3b-a274-d6cd3980d69d.png)

  3.The value of every barcode, and how many times every barcode appears in the image ( there could be repetitions of the barcode). This output
     could be printed.
     
   ![Screenshot from 2023-02-09 01-29-27](https://user-images.githubusercontent.com/87931949/217638404-2be7ac3e-d423-4e50-8c5f-3b825e01a901.png)
  
  4.Create bounding boxes of black color around each ITEM in the image ( not the barcode)
  
   ![Screenshot from 2023-02-15 23-11-03](https://user-images.githubusercontent.com/87931949/219109764-e7428cf5-067c-448a-b304-a96fb05629e2.png)

 *Installation*:
 
  1. Creating a virtual environment
    
    Link: https://www.geeksforgeeks.org/python-virtual-environment/
    
  2. 
