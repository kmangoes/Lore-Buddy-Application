# Software Requirements Specification Document 
## For Lore Buddy Application 
--- 

Version 0.1  
Prepared by Chase Solano  
12/27/2025  

Table of Contents  
=================  
* [Revision History](#revision-history)  
* 1 [Introduction](#1-introduction) 
  * 1.1 [Document Purpose](#11-document-purpose)
  * 1.2 [Product Scope](#12-product-scope)
* 2 [Product Overview](#2-product-overview)
  * 2.1 [Product Functions](#21-product-functions)
  * 2.2 [User Characteristics](#22-user-characteristics)
  * 2.3 [Assumptions and Dependencies](#23-assumptions-and-dependencies)
* 3 [Requirements](#3-requirements)
  * 3.1 [Functional Requirements](#31-functional-requirements)
    * 3.1.1 [User Interfaces](#311-user-interfaces)
    * 3.1.2 [Hardware Interfaces](#312-hardware-interfaces)
    * 3.1.3 [Software Interfaces](#313-software-interfaces)
  * 3.2 [Non-Functional Requirements](#32-non-functional-requirements)  

## Revision History 
| Name | Date    | Reason For Changes  | Version   |
| ---- | ------- | ------------------- | --------- |
|Chase |12/27/25 |    Edit SRS info    |    0.1    |
|      |         |                     |           |
|      |         |                     |           |

## 1. Introduction

### 1.1 Document Purpose 
This Software Requirements Specification (SRS) defines the requirements for Lore Buddy, a web application developed by myself for the purpose of showcasing and developing my skills in web development, secure data transmission and professional project management. The intended audience is writers and fans of lore-rich stories (even TTRPGs!) that would find necessity in the level of organization that Lore Buddy will provide for complicated fantasy universes. 

### 1.2 Product Scope  
Users will be able to:  
- Sign up/Log in with unique email and password credentials. If either already exist in system, cannot create a new account with them. 
- Create extensive family trees of their characters using both the character sheets and also directly adding new members to the tree. 
- Create timelines of story events. Like with family trees, events can be directly added to the timeline entity, or events can be assigned a timestamp in the events workspace. 
- Have their data **safely stored** using **AWS Cloud services** (want).  

## 2. Product Overview  

### 2.1 Product Functions  
- Different creation sheets for characters, events and environs. 
- Character and event sheets intrinsically build family trees and timelines, respectively. 
- Users can customize their workspace to an atmosphere that suits them. 

### 2.2 User Characteristics 
- The idea for this application was designed with what I as a writer wanted from a writing application, heavily catered towards organized in-depth lore creation. 

### 2.3 Assumptions & Dependencies 
- Security dependencies (**Spring Security?**) later on to ensure secure login 
- Integrating data with an AWS service for cloud storage realistic to a professional product
- Like other workspace apps that store data in the cloud (i.e., Notion), an internet connection will be needed for proper data syncing. (**offline mode want?**)