Author: Despereaux #(Brian Dao)

PingCheck help SysAdmin to get data quickly from IPAM and filter which IP is free or in used by ping. 
Then, in case IP blocked ICMP, this will continue check list IP free by netcat (Check Port Opened).


USAGE:
------

1. Install GIT Package:

  - sudo apt-get install git -y

2. Download PingCheck:

  - git clone https://github.com/D3spereaux/PingCheck.git

3. Go to the folder just downloaded & give permission file bash to Execute:

  - cd PingCheck
  - chmod +x checkipfree.sh

4. Run and enjoy the tool:

  - ./checkipfree.sh
