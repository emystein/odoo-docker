# Build a new image based on:
FROM odoo:14


# Example 1: Install new python libs in the new image
# RUN pip3 install --no-cache-dir paramiko

# Example 2: Install new python libs from the requirement file
COPY python3-requirements.txt /etc/
RUN pip3 install --no-cache-dir -r /etc/python3-requirements.txt
#RUN rm /etc/python3-requirements.txt
