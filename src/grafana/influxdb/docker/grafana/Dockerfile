FROM grafana/grafana:7.3.5
ADD ./provisioning /etc/grafana/provisioning
ADD ./config.ini /etc/grafana/config.ini
ADD ./dashboards /var/lib/grafana/dashboards
ENV GF_INSTALL_PLUGINS digrich-bubblechart-panel,savantly-heatmap-panel,grafana-piechart-panel,jdbranham-diagram-panel
