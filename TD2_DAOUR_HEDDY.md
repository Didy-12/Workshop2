# Torrent

BitTorrent is a leading software company with popular torrent client software for Windows, Mac, Android, and more.It is one of the most common protocols for transferring large files. BitTorrent breaks down large files into small pieces, which are distributed across a network of computers. As you download a piece, you also start uploading it to others, making the distribution faster as more users download the file.

## Download the Torrent package.
'''
npm install -g torrent
'''

## Check installation.
'''
torrent --version
'''

## Question 1 : Create a torrent containing this image.

<img width="397" alt="Capture d’écran 2024-02-10 à 22 21 35" src="https://github.com/Didy-12/Workshop2/assets/120495158/20627cfc-059b-4079-964f-a924a99542ab">
                                                    
<img width="115" alt="Capture d’écran 2024-02-10 à 22 22 44" src="https://github.com/Didy-12/Workshop2/assets/120495158/c4b8474d-b9e3-442f-bcf4-a3a503cc5754">

we can see the info off image.torrent by typing this command:
<img width="448" alt="Capture d’écran 2024-02-10 à 22 23 47" src="https://github.com/Didy-12/Workshop2/assets/120495158/9553ed7f-4fb2-44ec-be0c-f8e37f88d6a7">

## Question 2 : Now copy the image to a new directory named partition1 and create a torrent of this folder. What do you observe?

<img width="689" alt="Capture d’écran 2024-02-10 à 22 42 06" src="https://github.com/Didy-12/Workshop2/assets/120495158/e7ef4125-0fa8-49a7-878e-b809e34a1749">
<img width="489" alt="Capture d’écran 2024-02-10 à 22 42 41" src="https://github.com/Didy-12/Workshop2/assets/120495158/08f77f3d-b553-4631-a711-4115899590f0">

We can see that the chaton.jpeg file is inside the partition.torrent 

We also see that the hash if different than the one of the chaton.torrent.
## Question 3 : Copy the partition1 folder and then generate the associated torrent. What do you observe?

<img width="675" alt="Capture d’écran 2024-02-10 à 22 44 37" src="https://github.com/Didy-12/Workshop2/assets/120495158/3bc1958c-6075-4d93-9226-b81abab02c2d">

<img width="484" alt="Capture d’écran 2024-02-10 à 22 45 03" src="https://github.com/Didy-12/Workshop2/assets/120495158/7d7b90f9-f6df-4c8d-978c-24173b3bcbd5">

We see that the hash if different than the one of the partition1.


# IPFS

## Installation of IPFS

I have followed the different step explained in the Workshopo 2.

<img width="1340" alt="Capture d’écran 2024-02-10 à 22 49 31" src="https://github.com/Didy-12/Workshop2/assets/120495158/8b3f535d-eb82-41ff-98d7-77ba80cf0612">

## Question 1 : Upload the previous image to IPFS.

<img width="1259" alt="Capture d’écran 2024-02-10 à 22 50 44" src="https://github.com/Didy-12/Workshop2/assets/120495158/7ba11af3-c038-48c5-b0f2-f98eac60915c">

## Question 2 : Now upload partition1 to IPFS. What do you observe compared to the torrent part?

<img width="1171" alt="Capture d’écran 2024-02-10 à 22 52 39" src="https://github.com/Didy-12/Workshop2/assets/120495158/c6b6a34e-6f04-48f0-9d2d-0e3bece55f5e">
The main difference between Torrent and IPFS in this context is that Torrent relies on a centralized tracker to help share files, while IPFS operates in a decentralized manner, allowing it to share files without the need for such a tracker.

## Question 3 : Copy the partition1 folder and then generate the associated torrent. What do you observe?

<img width="1179" alt="Capture d’écran 2024-02-10 à 23 01 45" src="https://github.com/Didy-12/Workshop2/assets/120495158/055482f4-6abc-44d5-8f63-e794b095aa8d">
We can see that the CID is the same than the one of partition1.

















