FROM alpine:latest

# Copie de l'application dans le conteneur
COPY app.sh /app.sh

# Rend le script exécutable
RUN chmod +x /app.sh

# Commande exécutée au lancement du conteneur
CMD ["/app.sh"]
