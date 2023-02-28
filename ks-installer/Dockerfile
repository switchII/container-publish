FROM kubesphere/ks-installer:v3.3.1
USER root
RUN sed -i 's/self.verify_ssl = True/self.verify_ssl = False/g' /usr/local/lib/python3.10/site-packages/kubernetes/client/configuration.py
USER kubesphere