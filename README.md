# MESH SDK IRKit Tag

Exported Source of a MESH SDK IRKit Tag.

## Description

By using this tag,
you can control IRKit on Sony MESH Canvas.

***DEMO:***
[TODO]

## Features

- Learn Any IR command.
- Send learnd IR command.

## Supported IRKit version

This tag supports IRKit ver v3.0.0.gxxxxx now.
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
2. Now, you can find IRkit tag as custom tag   
on MESH application. Please add.

## Usage

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

## Author

Tetsunori.Nakayama
