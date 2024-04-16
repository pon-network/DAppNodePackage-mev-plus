ARG UPSTREAM_VERSION

FROM blockswap/pon-network-mev-plus:${UPSTREAM_VERSION}

WORKDIR /root/

COPY entrypoint.sh .

ENTRYPOINT [ "./entrypoint.sh" ]
