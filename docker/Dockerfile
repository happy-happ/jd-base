FROM node:15.9.0-alpine3.12
LABEL maintainer="Evine Deng"
ARG JD_BASE_URL=git@gitee.com:shuye72/jd-base.git
ARG JD_BASE_BRANCH=main
ARG JD_SCRIPTS_URL=git@gitee.com:shuye72/MyActions.git
ARG JD_SCRIPTS_BRANCH=main
ENV PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin \
    LANG=zh_CN.UTF-8 \
    SHELL=/bin/bash \
    PS1="\u@\h:\w \$ " \
    JD_DIR=/jd \
    ENABLE_HANGUP=true \
    ENABLE_WEB_PANEL=true
ARG KEY="-----BEGIN OPENSSH PRIVATE KEY-----\n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\n-----END OPENSSH PRIVATE KEY-----
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories \
    && apk update -f \
    && apk upgrade \
    && apk --no-cache add -f bash \
                             coreutils \
                             moreutils \
                             git \
                             wget \
                             curl \
                             nano \
                             tzdata \
                             perl \
                             openssl \
                             openssh \
    && rm -rf /var/cache/apk/* \
    && ln -sf /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
    && echo "Asia/Shanghai" > /etc/timezone \
    && mkdir -p /root/.ssh \
    && chmod 700 /root/.ssh \
    && cd /root/.ssh \
    && echo -e $KEY > /root/.ssh/id_rsa \
    && chmod 600 /root/.ssh/id_rsa \
    && ssh-keyscan gitee.com > /root/.ssh/known_hosts \
    && git clone -b ${JD_BASE_BRANCH} ${JD_BASE_URL} ${JD_DIR} \
    && cd ${JD_DIR}/panel \
    && npm install \
    && git clone -b ${JD_SCRIPTS_BRANCH} ${JD_SCRIPTS_URL} ${JD_DIR}/scripts \
    && cd ${JD_DIR}/scripts \
    && npm install \
    && npm install -g pm2 \
    && ln -sf ${JD_DIR}/jd.sh /usr/local/bin/jd \
    && ln -sf ${JD_DIR}/git_pull.sh /usr/local/bin/git_pull \
    && ln -sf ${JD_DIR}/rm_log.sh /usr/local/bin/rm_log \
    && ln -sf ${JD_DIR}/export_sharecodes.sh /usr/local/bin/export_sharecodes \
    && cp -f ${JD_DIR}/docker/docker-entrypoint.sh /usr/local/bin/docker-entrypoint.sh \
    && chmod 777 /usr/local/bin/docker-entrypoint.sh \
    && rm -rf /root/.npm
WORKDIR ${JD_DIR}
ENTRYPOINT ["docker-entrypoint.sh"]