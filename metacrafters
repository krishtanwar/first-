/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// create a variable to hold your NFT's
let NFTcount=0;

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
function mintNFT (name,job_designation,car_owned) {
const nft={
   name:name,
   job:job_designation,
   car:car_owned
};
NFTcount++;
return nft;
}

// create a "loop" that will go through an "array" of NFT's
const NFT_ARRAY=[];
const NFT_1=mintNFT("Chris","Assistant Professor","Mercedes");
NFT_ARRAY.push(NFT_1);
const NFT_2=mintNFT("Sam","Sales Manager","Honda");
NFT_ARRAY.push(NFT_2);
const NFT_3=mintNFT("Hellen","Youtuber","Porsche");
NFT_ARRAY.push(NFT_3);
// and print their metadata with console.log()
function listNFTs () {
for(let j=0;j<NFT_ARRAY.length;j++){
   const nft=NFT_ARRAY[j];
   console.log("Name:"+nft.name);
   console.log("Job:"+nft.job);
   console.log("Car:"+nft.car);
   console.log("______________");
}
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
console.log("Total Number of NFTs are:"+NFTcount);
}

// call your functions below this line
listNFTs();
getTotalSupply();
