Todo:




    * Change how menu looks
    * music
    * toggle music?

    * Visualise minion generation???

    /SOBOTA?
    * Network communication

    * adding new listeners (touch listener)
    * animations for changing squares?
    * animations



Done:

    * Add description
    * Added pictures to load
    * print why someone won
    * Choose more randomly players to attack
    * There is some attack bug???
    * stack trace unfinished with chosing new player...
    * There is a bug in drawing restriction for ONE_PLAYER
    * There is a bug for chosing different players
    * React when current_player looses (doesn't have any fields left)
    * REVERSING the objective?!

        * change the objective after some timeout (60 seconds)

        * objectives:

            * conquer all OBJECTIVE.CONQUER_ALL
            * conquer specific player OBJECTIVE.CONQUER_PLAYER
            * none OBJECTIVE.FREE


        * restrictions:

            * none RESTRICTION.NONE
            * only neutral can be attacked RESTRICTION.NEUTRAL
            * only players  RESTRICTION.PLAYERS
            * can't attack  RESTRICTION.PEACE
            * only specific player RESTRICTION.ONE_PLAYER

        * combos:

            * Mandatory:

                * OBJECTIVE.CONQUER_ALL & RESTRICTION.NONE
                * OBJECTIVE.FREE can't be with RESTRICTION.NONE

            * Optional

                * OBJECTIVE.CONQUER_PLAYER & RESTRICTION.PLAYERS
                * OBJECTIVE.CONQUER_PLAYER & RESTRICTION.ONE_PLAYER

                * OBJECTIVE.FREE & RESTRICTION.NEUTRAL
                * OBJECTIVE.FREE & RESTRICTION.PLAYERS
                * OBJECTIVE.FREE & RESTRICTION.PEACE
                * OBJECTIVE.FREE & RESTRICTION.ONE_PLAYER

        TODO: Message: Reversing objective!
        TODO: Objective indicator
        TODO: Restriction indicator

    * visualize winning dialog :D
    * winning dialog!
    * first page for the game!
    * remove middleground
    * checking winning conditions? :D
    * map generation - I will create types of maps manually, it will be nicer :)
    * bugs: monitor attacked_tile for user
    * check what happens if you choose to attack another square DONE
    * add attack posibilities for squares which are further away DONE
    * AI
    * Visualise how many minions can be generated per tile
    * Visualise minion health
    * Correcting attack algorithm, so that we can attack tiles of different players
    * review the conquest algorithm
    * defence algorithm
    * Create algorithm for when attacking the same tile by 2 players (or defend)
