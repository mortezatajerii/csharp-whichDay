<p align="center">
  <a href="" rel="noopener">
  <img width=200px height=200px src="images/logo_transparent.png" alt="Project logo"></a>
</p>

<h3 align="center">Which Day</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center">
  <b>Which Day</b> helps you figure out you're burned on 
  which day of the week and see alternative calendar dates for your birth date.
</p>

## &#129488; About <a name = "about"></a>

This a simple project for developing and increasing knowledge in c# based on a course by <a href="https://github.com/ashkanRmk">Ashkan Rahmani</a>  
Technologies I used in developing this project:  
  
.NET Core SDK version 3.1.426  
Virtual Studio Code  
Git  
  
If you have any messages for me, rich me by E-mail at
<a href="mailto: mortezatajerii@gmail.com">mortezatajerii@gmail.com</a>

## &#127937; Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

As prerequisites you will need to install `.NET SDK 3.1` and `git` installed on your computer.

#### Debian / Ubuntu / ZorinOS
```
wget https://packages.microsoft.com/config/ubuntu/21.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
```
```
sudo apt-get update
sudo apt-get install -y apt-transport-https
sudo apt-get update
sudo apt-get install -y git dotnet-sdk-3.1  

```
#### Arch / Manjaro / EndeavorOS
with an AUR helper like paru:
```
paru
paru -S  dotnet-core-3.1-bin
echo "export DOTNET_SYSTEM_GLOBALIZATION_INVARIANT=1" >> ~/.bashrc
```
### Installing

First, clone repository to your system

```
git clone https://github.com/mortezatajerii/csharp-whichDay.git
```

and change directory to that

```
cd csharp-whichDay
```
then run project
```
dotnet run
```
End with an example of getting some data out of the system or using it for a little demo.
```
>> Enter your birth date: #6-12-1380  
You burned on Monday  
25 February 2002   
```
    
## &#128231; Contact

If you have any messages for me, rich me by E-mail at
<a href="mailto: mortezatajerii@gmail.com">mortezatajerii@gmail.com</a>
