Welcome to **TreeLife,** your guide to learning about the beauty, diversity, and importance of trees around the world. 

---

## About Us
At **TreeLife,** we're passionate about forests and green living. 

Our mission is to:

• Educate people about the differet types of trees.

• Promote sustainable forestry.

• Encourage reforestation projects.

> "The best time to plant a tree was 20 years ago. The second best time is now."
>
> — *Chinese Proverb*

---

## **Featured Trees**
 
**Oak Tree**

**Scientific Name:** *Quercus robur*

Known for its strength and longevity, the oak is a symbol of endurance.
 
 ![tree from a game](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTYv9onR7lUafTh3klTrBr-vKd3-QKktu4zaA&s)

---

**Pine Tree**

**Scientific Name: *Pinus*

Evergreen and aromatic, pine trees thrive in colder regions.

![bonsai tree](https://media.istockphoto.com/id/155908124/photo/small-green-bonsai-tree-in-a-brown-plant-pot.jpg?s=612x612&w=0&k=20&c=GSbcXz_yoIFSwk5QF0vOUCk-hq0ULkhFTRBTfpQ25Yk=)

---

## **Tree Identification Tool**

You can use this simple **Javascript** function to identify a tree by its characteristics:

```
function identify_tree(leaf_shape, region){
    
    if(leaf_shape == "needle" && region == "cold"){
        
        return "Pine Tree"
    
    } else if(leaf_shape == "broad" && region == "temperate"){
        
        return "Oak Tree"
    
    } else {
        
        return "Unknown Tree"
    
    }

}

console.log(identify_tree("needle", "cold")}

```




