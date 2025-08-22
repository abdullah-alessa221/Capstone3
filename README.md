👤 Abdullah

Mainly focused on Tournament Management, building endpoints for handling tournaments, players, teams, and scheduling.
Implemented endpoints:

Get all tournaments → /get-tournamentsOutDTO

Get players in a specific tournament → /get-players-in-tournament/{tournamentId}

Randomly assign teams in a tournament → /{tournamentId}/determine-teams

Get teams of a tournament → /{tournamentId}/teams

Close a tournament (by sponsor) → /{sponsorId}/{tournamentId}/close

Get tournament(s) for a specific player (by email) → /get-player-tournament/{email}

Get all open tournaments → /get-open-tournaments

Get remaining players until a tournament is full → /get-remaining-players/{tournamentId}

Get tournaments by category → /get-by-category/{categoryId}

Get tournaments by sponsor → /get-by-sponsor/{sponsorId}

Reschedule a tournament → /reschedule-tournaments/{sponsor_id}/{tournamentId}







