FROM rclone/rclone:1.74

COPY entrypoint.sh /usr/local/bin/entrypoint.sh
RUN chmod +x /usr/local/bin/entrypoint.sh

# overwrite the entrypoint
ENTRYPOINT ["/usr/local/bin/entrypoint.sh"]
