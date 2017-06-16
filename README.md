### Pepe Chain

How to verify Rare Pepe integrity:

1. Clone Repository
2. Download latest Rare Pepe list at http://rarepepedirectory.com/json/pepelist.json and save to ```pepe_directory```
3. Open Terminal, go to the Pepe Chain root directory
4. Type ```node scrape_pepe_directory``` and press enter
5. After all images are downloaded, type ```php verify.php``` and press enter
6. Compare asset and image merkle root with published value.  
7. To compare with value listed below, specify count by typing ```php verify.php 215```, ```php verify.php 283```, etc.



````
<<<<<<< Updated upstream
Count: 395
Asset Hash Merkle Root: 23117973a5aa49b79dc28466493fa086a6ea0d8a66c39762ee510b2476b63062
Image Hash Merkle Root: 7b6180568858d012fd4a2cf88a57199ae95a9ba26418b37bdfe8bdb1a99cc37b
=======
Count: 999
Asset Hash Merkle Root: 3425cdb30ba3b2be84ddefe231da2eae11dca08675493cd5aa8b8e3ba1cda5ed
Image Hash Merkle Root: 8587d3e76980f4f398e705509d99a2c7d18a1fc604115ed016df4069d62a22aa
>>>>>>> Stashed changes
````

*Hashes Updated 15-Jun-17*
