# MIB files
## 📗 Table of contents
* [📖 About the repository](#about-the-repo)
* [💻 Getting started](#getting-started)
	* [Installation](#installation)
	* [Use example(s)](#use-examples)
	* [Structure of the project](#structure-project)
* [🔭 Roadmap](#roadmap)
* [👥 Contact](#contact)
* [🤝 Contributing](#contributing)


## 📖 About the repository <a name="about-the-repo"/>
A repository with over 10k of MIB files in JSON and ASN.1 format from different manufacturer's website, GitHub repositories, databases on the web, etc.


## 💻 Getting started <a name="getting-started"/>
### Installation
To retrieve all the MIB files:
```sh 
git clone https://github.com/MizaruIT/MIBS
cd MIBS;
```

### Use example(s) <a name="use-examples"/>
**Adding to the Linux DB**
You can add the MIB files into the directory **/usr/share/snmp/mibs**, thus when using snmp tools, you will get more information.
```sh
# From the MIBS directory
cp ASN1-FORMAT/*.mib /usr/share/snmp/mibs/*.txt
```

### Structure of the project <a name="structure-project"/>
The project has the following structure with the different format of files for MIB.

    ├── ASN1-FORMAT         # The MIB files in an ASN.1 format
    └── JSON-FORMAT         # The MIB files in a JSON format

  ## 🔭 ROADMAP <a name="roadmap"/>
- [ ] Add more MIB files


## 👥 Contact <a name="contact"/>
- Twitter: @MizaruIT (https://twitter.com/MizaruIT)
- GitHub: @MizaruIT (https://github.com/MizaruIT)
- Project Link: https://github.com/MizaruIT/MIBS


## 🤝 Contributing <a name="contributing"/>
Contributions, issues, and feature requests are welcome!

Feel free to send me messages to add new MIB files.
