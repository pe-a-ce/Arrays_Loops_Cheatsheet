

# ARRAYS
| Syntax | Description |
| ----------- | ----------- |


# ARRAY LISTS

- multipe values of the same data type for a single variable
- no fixed size 

| Syntax | Description |
| ----------- | ----------- |
|Arrayname.add("value")|To add to ArrayList
| System.out.println(scottishIslands.indexOf("Value"));| Print out the index position of "Value"
|scottishIslands.remove("Tresco");| Remove "Tresco" from the list by name
|scottishIslands.remove(5);| Remove "Arran" from the list by index 
|Collections.sort(scottishIslands);| Sort the list alphabetically
|System.out.println(scottishIslands.size());| System.out.println(scottishIslands.size());
|Print the sum of the numbers|  
| System.out.println(betterShoppingList.contains("milk")); | check if item is present (true or false)



# MAP (HASHMAP)

- Consists of key-value pairs 
- Can search by the key to extract the value
- Needs 2 data types to be defined; the datatype of the key and of the associated values (i.e. string and integer)

Example: HashMap<String, Integer> mappedShoppingList = new HashMap();

| Syntax | Description |
| ----------- | ----------- |
|  mapName.put("label", associated value);| adding a value
| System.out.println(mappedShoppingList.get("milk")); | retrieve associated values 
mappedShoppingList.remove("eggs");| remove key and its associated value
|mappedShoppingList.replace("bread", 6);|  replace
|mappedShoppingList.replace("milk", null);| updating a value
|System.out.println(mappedShoppingList.keySet());| to see all keys
|System.out.println(mappedShoppingList.values());| to see all values


# LOOPS 
## For Loops

3 pieces of information is needed:
1. Initial Value
2. Termination/Stop Condition 
    - only stops when condition is false 
3. Increment 
    - happens after each iteration

SystemPrint is executed after each iteration

can be made to be as complex as needed

for (int i=1; i <=10; i++){

    system.out.println(i);
}


| Syntax | Description |
| ----------- | ----------- |
