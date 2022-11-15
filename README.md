# Repositorio

from ds4 import
        
        # if the cell is not assigned then ignore it
        if games_data == 'Not assigned':
            games = []
        # else process the data and add it to the dictionary
        else:
            games_codes_dict[games_code] = {}
            
            try:
                games = games_data.split('(')[1]
            
                # remove parantheses from gamesstring
                games = ngames.replace('(', ' ')
                games = games.replace(')', ' ')

                games_names = games.split('/')
                games_clean = ', '.join([name.strip() for name in games_names])
            except:
                borough = borough.strip('\n')
                games_clean = borough
 
            # add borough and games to dictionary
            games_codes_dict[postal_code]['borough'] = borough
            games_codes_dict[postal_code]['games'] = games_clean
    except:
        pass
     games_codes_dict[postal_code]['borough'] = borough games_codes_dict[postal_code]['borough'] = borough
 games_codes_dict[postal_code]['borough'] = borough
                 try:
                games = games_data.split('(')[1]
             try:
                games = games_data.split('(')[1]
                # if the cell is not assigned then ignore it
        if games_data == 'Not assigned':
            games = [1]
             except:
                borough = borough.strip('\n')
                games_clean = borough
                
            
