# Copyright (c) 2020 Oracle and/or its affiliates.
# Licensed under the Universal Permissive License v 1.0 as shown at https://oss.oracle.com/licenses/upl.
FROM oraclelinux:8-slim

COPY nodejs.module /etc/dnf/modules.d/nodejs.module

RUN microdnf install nodejs npm && \
    microdnf clean all

CMD ["/bin/node", "-v"]
