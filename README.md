scp -i .\voice-backend-key.pem -r C:\Users\rufia\Desktop\TESTAIAGENT\rapidcall-ai\* ubuntu@18.158.9.53:/opt/rapidcallai/rapidcall-ai/

sudo mkdir -p /opt/rapidcallai/rapidcall-ai
sudo mv /tmp/rapidcall-ai/* /opt/rapidcallai/rapidcall-ai/