FROM registry.local:38080/frame_system/matlab:r2022a-cuda12.1-py3.10

COPY --chown=${NB_UID}:${NB_GID} . ${HOME}

WORKDIR ${HOME}