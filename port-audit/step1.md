Follow the installation instructions below:

1. Clone this repo in your local machine typing on your terminal:

    `git clone https://github.com/agmanuelian/PortAudit.git`{{execute}}

2. Install the required dependencies specified on the *requirements.txt* file:

    `cd PortAudit`{{execute}}
    
    `pip install -r requirements.txt`{{execute}}

3. Edit the *routers.csv* file with the parameters (IP address and RESTCONF port) of the list of devices that you want to configure.

    ![Input CSV file, with the list of devices to audit](https://raw.githubusercontent.com/agmanuelian/PortAudit/master/screenshots/routers_csv.png)

    `cat routers.csv`{{execute}}

4. Modify on the *port_audit.py* script the directory from where the *routers.csv* file is read, specifying your local directory. Also, modify the directory where *output_interfaces.csv* will be written to.

    `sed -i 's!/path_to_file/routers.csv!./routers.csv!g' port_audit.py`{{execute}}

    `sed -i 's!/destination_path_to_file/output_interfaces.csv!./output_interfaces.csv!g' port_audit.py`{{execute}}
