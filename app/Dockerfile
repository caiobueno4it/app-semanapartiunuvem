# Build the runtime image
FROM mcr.microsoft.com/dotnet/aspnet:6.0.21
WORKDIR /app
COPY . .

# Expose the necessary port
EXPOSE 80

# Start the application
ENTRYPOINT ["dotnet", "Badges.dll"]
