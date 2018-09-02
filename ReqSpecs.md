# Requirements specifications for E voting system vusrote

## Summary

Vusrote shall enable a simple and secure voting for any kind of decisions. Its main focus 
is making reliable and retracable decisisions for communities. 

## Notes
In this document I do address male and female but use only male wording.

## Functional description

Each voting shall be recorded. All votes shall be tracable for each member of the community.

### Communities
A member is part of a community. A member can be part of several communities. Each member
can set up a community. A member must be part of at least one community. If the community
does not exists, the member has to create it.

### Setting up a vote
Any member of the community shall be able to set up a vote. Optionally, this can be restricted
to one or more members. The member who starts a vote is called vote executer.

The vote executer provides the topic as text throught the web interface. The text has to be 
a clear description of the problem. The text shall only allow a yes or no interpretation.
Optionally, the vote executer uploads an electronical document on which content the vote 
shall be.

The vote executer sets the time frame of the vote. A vote must last a limited amount of time.

Optionally, the vote executer selects the members which shall vote. Otherwise all members of
the community shall be allowed to vote.

### Joining a vote
A member logs in with his/her password. If a vote is currently running, the member can order
a token. The token is valid for a specific amount of time (set by the voting executer). The
member can never have multiple tokens for a single vote.

### Voting
The member logs in into vusrote. He selects the vote in which he wants to participate. If he
has a token for this specific vote, he selects his choise. He can only vote once. Then, the
token is consumed. If he wants to change his vote afterwards, he has to contact the vote
executer, who decides if he can change is vote. If yes, the member gets a new token.

### Presenting the result
Each vote lasts a limited amount of time set by the vote executer. If the time is up, the vote
is summerized. The vote executer gets an email with the result. If the vote of public, the
voters choices are listed with their names. If the vote was non-public, only the result is
shown. It might be possible to print the result as a non-changable pdf for the communities
records.

Each vote with the result shall be stored and be retracable every time for each member.
