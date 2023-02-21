# srsRAN_docs
Documentation for srsRAN software suite - see [docs.srsran.com](http://docs.srsran.com)

This is the common landing page for the srsRAN Project and srsRAN 4G.

See the [srsRAN Project](http://github.com/srsran/srsran_4g_docs) and [srsRAN 4G](http://github.com/srsran/srsran_project_docs) for more details.

# Local Installation 

The docs require multiple sphinx extensions. 

On Ubuntu, they can be installed with:
```
sudo apt install python3-pip
pip3 install -r requirements.txt
```

Once these are installed, you can download and build the docs with the following: 

```
git clone https://github.com/srsRAN/srsRAN_docs.git
cd srsRAN_docs/docs
make html
```

Then load the compiled doc in your browser
```
firefox build/html/index.html
google-chrome build/html/index.html
```

To enable live build previews when editing documentation install the following extension: 
  
- sphinx-autobuild 

To build the docs first run from /docs/source
```
sphinx-build -b html . .build
```

Then run the following command from the docs main folder
```
sphinx-autobuild docs/source/ docs/source/.build/html
```
This will start a server at http://127.0.0.1:8000 which can be viewed in your browser, any changes to the docs will be shown here once saved. 
