
# DeepScan
# What is it
Deepscan is a Docker based solution for security testing software. The solution includes a simple web interface, using which you can do:\
     . Vulnerability testing of websites \
     . Network scanning\
     . Cloud security\
     . Webserver security\
     . Code security\
     . Open-source dependency vulnerability\
     
# How To
Download the deepscan.zip. Unzip to a folder (say, d:\deepscan):\
	1. Start docker daemon on your machine, if not already.\
	2. cd D:\deepscan\
	3. Run the command:\
		For Windows:  run.cmd \
		For *inx (such as Ubuntu/Centos etc):\
				chmod +x run.sh\
				./run.sh				\
	Note: First time can take upto 10 minutes while all docker images are pulled/built.\
	5. Open your browser and navigate to http://localhost:5021. You can perform various security tests using the UI.\
	6. To stop: stop.cmd  (or ./stop.sh for *inx)\
 
# Required
1. You need to have Docker along with compose installed on your machine. You may download it from https://docs.docker.com/compose/install/\


     
