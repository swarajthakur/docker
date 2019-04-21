ARG ELK_VERSION

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/beats/metricbeat:${ELK_VERSION}
RUN /bin/bash -c './metricbeat modules enable docker system'
# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>