## S.M.A.R.T. HDD Status NewRelic plugin

This plugin sends S.M.A.R.T. metrics to NewRelic.

#### Installation

1. Copy `config/template_newrelic_plugin.yml` to `config/newrelic_plugin.yml`
2. Edit `config/newrelic_plugin.yml` and replace the values:
  * 'YOUR_LICENSE_KEY_HERE' with your New Relic license key
  * `your.host.name` with your host name
  * `drives` parameter with a list of drives to process
  * set `report_old_age` to true if you want to send "Old age" type attributes to NewRelic
3. Create a plugin in New Relic
4. run `./newrelic_smartstatus_agent`

