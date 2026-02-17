# Restart Wazuh Manager
sudo systemctl restart wazuh-manager

# Test SSH failures
ssh user@192.168.1.x

# Monitor logs
sudo tail -f /var/log/auth.log
