FROM ansible/ansible-runner
ENV ANSIBLE_HOST_KEY_CHECKING=False
RUN dnf install -y git

ENV PATH="/opt/bin:${PATH}"

COPY bin/ /opt/bin

ENTRYPOINT [ "" ]