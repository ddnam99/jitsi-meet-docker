1. cp env.example .env && ./gen-passwords.sh
2. mkdir -p config/{web/letsencrypt,transcripts,prosody,jicofo,jvb,jigasi,jibri}
3. docker-compose up -d
4. Access https://localhost:8443/

### Custom Front-end (folder: jitsi-meet)
### Custom Function (folder: config/web/(config|interface-config).js)