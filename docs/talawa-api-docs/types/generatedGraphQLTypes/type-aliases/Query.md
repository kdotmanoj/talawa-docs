[**talawa-api**](../../../README.md) • **Docs**

***

[talawa-api](../../../modules.md) / [types/generatedGraphQLTypes](../README.md) / Query

# Type Alias: Query

> **Query**: `object`

## Type declaration

### \_\_typename?

> `optional` **\_\_typename**: `"Query"`

### actionItemCategoriesByOrganization?

> `optional` **actionItemCategoriesByOrganization**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`ActionItemCategory`](ActionItemCategory.md)\>[]\>

### actionItemsByEvent?

> `optional` **actionItemsByEvent**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`ActionItem`](ActionItem.md)\>[]\>

### actionItemsByOrganization?

> `optional` **actionItemsByOrganization**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`ActionItem`](ActionItem.md)\>[]\>

### adminPlugin?

> `optional` **adminPlugin**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Plugin`](Plugin.md)\>[]\>

### advertisementsConnection?

> `optional` **advertisementsConnection**: [`Maybe`](Maybe.md)\<[`AdvertisementsConnection`](AdvertisementsConnection.md)\>

### agendaCategory

> **agendaCategory**: [`AgendaCategory`](AgendaCategory.md)

### agendaItemByEvent?

> `optional` **agendaItemByEvent**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`AgendaItem`](AgendaItem.md)\>[]\>

### agendaItemByOrganization?

> `optional` **agendaItemByOrganization**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`AgendaItem`](AgendaItem.md)\>[]\>

### agendaItemCategoriesByOrganization?

> `optional` **agendaItemCategoriesByOrganization**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`AgendaCategory`](AgendaCategory.md)\>[]\>

### checkAuth

> **checkAuth**: [`User`](User.md)

### customDataByOrganization

> **customDataByOrganization**: [`UserCustomData`](UserCustomData.md)[]

### customFieldsByOrganization?

> `optional` **customFieldsByOrganization**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`OrganizationCustomField`](OrganizationCustomField.md)\>[]\>

### directChatById?

> `optional` **directChatById**: [`Maybe`](Maybe.md)\<[`DirectChat`](DirectChat.md)\>

### directChatsByUserID?

> `optional` **directChatsByUserID**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`DirectChat`](DirectChat.md)\>[]\>

### directChatsMessagesByChatID?

> `optional` **directChatsMessagesByChatID**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`DirectChatMessage`](DirectChatMessage.md)\>[]\>

### event?

> `optional` **event**: [`Maybe`](Maybe.md)\<[`Event`](Event.md)\>

### eventVolunteersByEvent?

> `optional` **eventVolunteersByEvent**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`EventVolunteer`](EventVolunteer.md)\>[]\>

### eventsByOrganization?

> `optional` **eventsByOrganization**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Event`](Event.md)\>[]\>

### eventsByOrganizationConnection

> **eventsByOrganizationConnection**: [`Event`](Event.md)[]

### fundsByOrganization?

> `optional` **fundsByOrganization**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Fund`](Fund.md)\>[]\>

### getAgendaItem?

> `optional` **getAgendaItem**: [`Maybe`](Maybe.md)\<[`AgendaItem`](AgendaItem.md)\>

### getAgendaSection?

> `optional` **getAgendaSection**: [`Maybe`](Maybe.md)\<[`AgendaSection`](AgendaSection.md)\>

### getAllAgendaItems?

> `optional` **getAllAgendaItems**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`AgendaItem`](AgendaItem.md)\>[]\>

### getAllNotesForAgendaItem?

> `optional` **getAllNotesForAgendaItem**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Note`](Note.md)\>[]\>

### getCommunityData?

> `optional` **getCommunityData**: [`Maybe`](Maybe.md)\<[`Community`](Community.md)\>

### getDonationById

> **getDonationById**: [`Donation`](Donation.md)

### getDonationByOrgId?

> `optional` **getDonationByOrgId**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Donation`](Donation.md)\>[]\>

### getDonationByOrgIdConnection

> **getDonationByOrgIdConnection**: [`Donation`](Donation.md)[]

### getEventAttendee?

> `optional` **getEventAttendee**: [`Maybe`](Maybe.md)\<[`EventAttendee`](EventAttendee.md)\>

### getEventAttendeesByEventId?

> `optional` **getEventAttendeesByEventId**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`EventAttendee`](EventAttendee.md)\>[]\>

### getEventInvitesByUserId

> **getEventInvitesByUserId**: [`EventAttendee`](EventAttendee.md)[]

### getFundById

> **getFundById**: [`Fund`](Fund.md)

### getFundraisingCampaignPledgeById

> **getFundraisingCampaignPledgeById**: [`FundraisingCampaignPledge`](FundraisingCampaignPledge.md)

### getFundraisingCampaigns

> **getFundraisingCampaigns**: [`Maybe`](Maybe.md)\<[`FundraisingCampaign`](FundraisingCampaign.md)\>[]

### getNoteById

> **getNoteById**: [`Note`](Note.md)

### getPledgesByUserId?

> `optional` **getPledgesByUserId**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`FundraisingCampaignPledge`](FundraisingCampaignPledge.md)\>[]\>

### getPlugins?

> `optional` **getPlugins**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Plugin`](Plugin.md)\>[]\>

### getVenueByOrgId?

> `optional` **getVenueByOrgId**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Venue`](Venue.md)\>[]\>

### getlanguage?

> `optional` **getlanguage**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Translation`](Translation.md)\>[]\>

### groupChatById?

> `optional` **groupChatById**: [`Maybe`](Maybe.md)\<[`GroupChat`](GroupChat.md)\>

### groupChatsByUserId?

> `optional` **groupChatsByUserId**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`GroupChat`](GroupChat.md)\>[]\>

### hasSubmittedFeedback?

> `optional` **hasSubmittedFeedback**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]\>

### isSampleOrganization

> **isSampleOrganization**: [`Scalars`](Scalars.md)\[`"Boolean"`\]\[`"output"`\]

### joinedOrganizations?

> `optional` **joinedOrganizations**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Organization`](Organization.md)\>[]\>

### me

> **me**: [`UserData`](UserData.md)

### myLanguage?

> `optional` **myLanguage**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"String"`\]\[`"output"`\]\>

### organizations?

> `optional` **organizations**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Organization`](Organization.md)\>[]\>

### organizationsConnection

> **organizationsConnection**: [`Maybe`](Maybe.md)\<[`Organization`](Organization.md)\>[]

### organizationsMemberConnection

> **organizationsMemberConnection**: [`UserConnection`](UserConnection.md)

### plugin?

> `optional` **plugin**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Plugin`](Plugin.md)\>[]\>

### post?

> `optional` **post**: [`Maybe`](Maybe.md)\<[`Post`](Post.md)\>

### registeredEventsByUser?

> `optional` **registeredEventsByUser**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`Event`](Event.md)\>[]\>

### registrantsByEvent?

> `optional` **registrantsByEvent**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`User`](User.md)\>[]\>

### user

> **user**: [`UserData`](UserData.md)

### userLanguage?

> `optional` **userLanguage**: [`Maybe`](Maybe.md)\<[`Scalars`](Scalars.md)\[`"String"`\]\[`"output"`\]\>

### users?

> `optional` **users**: [`Maybe`](Maybe.md)\<[`Maybe`](Maybe.md)\<[`UserData`](UserData.md)\>[]\>

### usersConnection

> **usersConnection**: [`Maybe`](Maybe.md)\<[`UserData`](UserData.md)\>[]

### venue?

> `optional` **venue**: [`Maybe`](Maybe.md)\<[`Venue`](Venue.md)\>

## Defined in

[src/types/generatedGraphQLTypes.ts:2263](https://github.com/PalisadoesFoundation/talawa-api/blob/fe65d855b3d1e3e4af621340e7e8bfa0325634c1/src/types/generatedGraphQLTypes.ts#L2263)
