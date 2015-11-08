# MESH SDK IRKit Tag

Exported Source of a MESH SDK IRKit Tag.

## Description

By using this tag,  
you can control IRKit on Sony MESH Canvas.  
[Details](https://tetunori.github.io/MESH_SDK_IRKit_tag/IRKit_gorgeous_view.htm)

***DEMO:***
[TODO]

## Features

- Learn Any IR command.
- Send learned IR command.
- Support both local and internet functions.

## Supported IRKit version

This tag supports IRKit ver 3.0.0.0.gxxxxx now.  
I confirmed with IRKit ver 3.0.0.0.g85190b1.

## Requirement

- MESH application
- SDK account

## Installation

### 1) on MESH SDK

1. Create a New tag and copy Exported_JSON_Data.txt,  
then paste it into "imported JSON Data" region.
2. Click "Load JSON" button and Save IRKit tag.

### 2) on MESH application
2. Now, you can find IRKit tag as custom tag
on MESH application. Please add.

## Usage
### 1) Local function
1. Prepare IP Address of IRKit.  
1-1. Refer to the [IRKit WebSite](http://getirkit.com/#IRKit-Device-API) to get IP Address of IRKit. Then, set it into the "IP Address" in IRKit tag Setup screen.  
<img src="https://github.com/tetunori/MESH_SDK_IRKit_tag/raw/master/img/4.png" alt="4.png" width="300">  

2. Learn IR Command.  
2-1. Send an IR command to IRKit from your IR remote controller.  
2-2. Connect any tag to the "Learn" Connector and trigger it.  
Then, IRKit tag saves learned the IR code.  
<img src="https://github.com/tetunori/MESH_SDK_IRKit_tag/raw/master/img/2.png" alt="2.png" width="300">  

3. Send IR command.  
3-1. Connect any tag to the "Send" Connector and trigger it.  
Then, IRKit tag requests IRKit to issue the IR code that is learned in 2-2.  
<img src="https://github.com/tetunori/MESH_SDK_IRKit_tag/raw/master/img/3.png" alt="3.png" width="300">  

### 2) Internet function
1. Prepare IP Address of IRKit.  
1-1. Refer to the [IRKit WebSite](http://getirkit.com/#IRKit-Device-API) to get IP Address of IRKit. Then, set it into the "IP Address" in IRKit tag Setup screen.  
<img src="https://github.com/tetunori/MESH_SDK_IRKit_tag/raw/master/img/5.png" alt=“5.png" width="300">  

2. Register for “Internet” function.  
2-1. Connect any tag to the “Register” Connector and trigger it.  
Then, IRKit tag sends registration command for “Internet” function to IRKit.  
<img src="https://github.com/tetunori/MESH_SDK_IRKit_tag/raw/master/img/6.png" alt=“6.png" width="300">  

3. Learn IR Command.  
3-1. Send an IR command to IRKit from your IR remote controller.  
3-2. Connect any tag to the "Learn" Connector and trigger it.  
Then, IRKit tag saves learned the IR code(via Internet).  
<img src="https://github.com/tetunori/MESH_SDK_IRKit_tag/raw/master/img/7.png" alt=“7.png" width="300">  

4. Send IR command.  
4-1. Connect any tag to the "Send" Connector and trigger it.  
Then, IRKit tag requests IRKit to issue the IR code that is learned in 3-2(via Internet).  
<img src="https://github.com/tetunori/MESH_SDK_IRKit_tag/raw/master/img/8.png" alt=“8.png" width="300">  

## Author

Tetsunori.Nakayama
