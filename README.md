#### about
this is a way to split up reciepts between groups

#### key ideas
- no cell service required
- automatic OCR and highlighting
- automatic currency conversion

#### resources
- https://medium.com/@errahulrajkumargupta/transferring-file-over-bluetooth-low-energy-in-ios-1f5222c384b9
- https://www.appcoda.com/ios7-airdrop-programming-tutorial/
    - use a special extension for the app so the airdrop prompt says to "Open With ReSplit"
    - encode metadata untop of the image within the custom format
        ```javascript 
        {
            image_data: DATA,
            prices: {"11.50": "Unassigned", 
                "19.20": UUID_1,
                "$52.49": TOTAL
            }
        }
        ```
    - split it image into rows and have people claim rows
        - row 1, 2, and 5 belong to jack
        - row 3, 6, 8 belong to saddie
        - row 10 is the total

