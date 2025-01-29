<h1>PfSense-Troubleshooting & FAQ</h1>

<h2>Description</h2>
If you are having issues with your PfSense firewall here are some common tips and tricks that I have learned to resolve various issues
<br/>

<h2>Not getting an IP on WAN</h2>

- First restart your modem then your PfSense
- If issue is not resolved try to spoof your MAC address of your ISP provided router into PfSense restart and reassess.
- If issue is still not resolved call your ISP for support and check if they support 3rd party routers.
- If still not working turn off your modem plug it into your PfSense firewall WAN port reinstall your PfSense with WAN plugged in and reconfigure everything.
- If all else fails try a different port for your WAN as the port you are trying to use may have a malfunction.

<h2>I have a WAN ip but not getting internet to any of my subnets</h2>

- Check your firewall rules and make sure ....
- Check and see if your DHCP servers are running if not turn them on.
- Have you tried turning your PfSense off and on again?

  <h2> </h2>
