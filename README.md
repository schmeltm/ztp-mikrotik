# ztp-mikrotik
Zero Touch Provisioning on Mikrotik

This repository contain python script to doing Zero Touch Provisioning on Mikrotik

<h3>Topology</h3>
This repository is tested using this Topology
<img src="Topology.png">

<h3>Requirement</h3>
To run this repository, you need some python library installed on your computer.
<ul>
    <li>Python 3.6.5</li>
    <li>flask</li>
    <li>paramiko</li>
    <li>telepot</li>
</ul>


<h3>Setup</h3>
<ol>
    <li>Create Telegram bot, this telegram bot will used to notify us if the provisioning on Mikrotik completed. You can follow tutorial on https://docs.microsoft.com/en-us/azure/bot-service/bot-service-channel-connect-telegram?view=azure-bot-service-4.0</li>
    <li>Clone this repository</li>
        <ol>
            <li>git clone https://github.com/arrosid/ztp-mikrotik.git</li>
            <li>cd ztp-mikrotik</li>
        </ol>
    <li>Install requirement library</li>
        <ol>
            <li>pip install -r requirement</li>
        </ol>
    <li>Run the python script</li>
        <ol>
            <li>python3 ztp_mikrotik.py</li>
        </ol>
    <li>Configure PPPoE Server on ISP</li>
    <li><i>Add ppp_script_on_up.txt</i> to the on UP script in the PPP Server Profile. Modify the "<your_flask_server_ip_address>" become your Server IP Address </li>
    <li></li>
</ol>