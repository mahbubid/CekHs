# CekHs
Cek Hse Rate for etherum mining, auto reset machine if droping hase rate.


HS Rate ceker, and auto restart mahine miner, ethermine pool.
Requir :
1. Rasp Pi 3
2. Relay Modul
3. Install Python
4. Ethermine pool

Step :
1. Assembl your HW req
2. Setup install

download extract dir "HsCek"

open "setingku.py"
wallet : ....
typing or insert your eth wallet

worker : ...
rig number, pin of relay and target of hs rate.

open in terminal pi, type "crontab -e" enter, in last row insert this:
"@reboot sudo python /home/yout/directory/cekHashRate.py"
if done, "ctrl+x"
#reboot


More info : fb,twt,ig @idmahbub
thanks, mahbub.my.id, www.wicsolution.com