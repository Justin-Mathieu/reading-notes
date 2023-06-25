
# Hash Tables

## Hash

- An algorith that tkes in a string and converts to a value.  
- Used for security.  
- Used to find index.  

## Bucket

- The content of the index.  
- Could contain more indexed buckets(collision?).

## Use

- Hash tables use key value pairs with every bucket.  
- Used to store key and quickly find specific data.  
- Hash maps to location.  
- O(1) time complexity.  

## Structure

- Output = input. Be specific.  
- Usually created from array.  

## Collisions

- More than one to a hash.  
- Should bot have collisions.  
- Keys that hash to same value should overwrite.  
- Solved by using linked list and utilizing the nodes.  
- Key and value should be stored in bucket.  

## How to use

- Add ascii values.  
- Multiply by prime number.  
- Divide by array length to get remainder.  
- Insert at that index.  

## Methods

- Get()
  - Takes in key, gets hash.
  - You need to go through bucket.  

- Has()
  - Takes iun a key,returns boolean if key exists.  
  - Call contains on hash mehthod?

- Keys()
  - Returns array of hash keys.  

- Hash()
  - Takes in string, returns a index for the bucket.  
