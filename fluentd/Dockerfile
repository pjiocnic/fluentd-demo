FROM fluent/fluentd:v1.6-debian-1
USER root
RUN gem install \
        fluent-plugin-elasticsearch \
        fluent-plugin-rewrite-tag-filter \
        fluent-plugin-detect-exceptions \
        fluent-plugin-forest \
        fluent-plugin-record-reformer \
        fluent-plugin-filter-docker_metadata \
        fluent-plugin-filter_typecast \
        fluent-plugin-filter_empty_keys
USER fluent

