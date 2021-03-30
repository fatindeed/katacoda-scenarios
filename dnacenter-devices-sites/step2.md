Here are some samples for the the script run for few different user provided values:

----------

1. Run the script

    `python devices_sites.py`{{execute}}

2. Enter `NYC`{{execute}}

3. Output:

    > The location with the name "Global/NYC", address: "111 8th Ave, Manhattan, New York, New York 10011, United States",
    > has these devices: NYC-ACCESS, NYC-RO

----------

1. Run the script

    `python devices_sites.py`{{execute}}

2. Enter `SJC`{{execute}}

3. Output:

    > The input "SJC", is not a match for any network devices or sites names

----------

1. Run the script

    `python devices_sites.py`{{execute}}

2. Enter `PDX-RO`{{execute}}

3. Output:

    > The device with the name "PDX-RO" location is: "Global/PDX/Floor 3", address: "5400 Meadows Road, Lake Oswego, Oregon 97035, United States"

----------

This script may be useful as part of integrations with other workflows for device inventory or network troubleshooting.