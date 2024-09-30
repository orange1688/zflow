# zflOw Project
This repository provides a regularly updated blacklist of IPs that can be used by network administrators to block malicious traffic.
1. `blacklist_ddos`: Contains IPs associated with Distributed Denial o
2. `blacklist_threat`: Contains IPs related to general threats and malicious activities.
3. `EDU_GOV_CTR_TW_IPDB`: Contains IPs associated with academic institutions and Taiwanese government entities.
Each blacklist is available in two formats:
- `.txt`: A simple, line-separated text format.
- `.json`: A structured JSON format for easier integration with various tools.

## Usage
You can download the appropriate blacklist file(s) and integrate them into your system or firewall configuration to enhance security. These blacklists are designed to help reduce unwanted traffic but do not guarantee complete protection.

### Available Files
- `blacklist_ddos.txt`: A text file containing IPs associated with DDoS attacks.
- `blacklist_ddos.json`: A JSON file containing the same list of IPs.
- `blacklist_threat.txt`: A text file containing IPs associated with general threats.
- `blacklist_threat.json`: A JSON file containing the same list of IPs.
- `EDU_GOV_CTR_TW_IPDB.txt`: A text file containing IPs associated with academic institutions and Taiwanese government entities.
- `EDU_GOV_CTR_TW_IPDB.json`: A JSON file containing the same list of IPs.
- `url_filter/{category}_{ip/domain}.{json/txt}`: A text/json file containing IPs or Domains associated with various content categories, including {category}. This list can be used to create blocking rules to restrict access to inappropriate, harmful, or unwanted content based on specific categories.

## Disclaimer
This project and its content are provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the project or the use or other dealings in the project.

**Please note** that this blacklist may contain false positives and should not be relied upon as the sole source of information when configuring your network security.

## License
This project is licensed under the MIT License.
