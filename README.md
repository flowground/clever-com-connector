# ![LOGO](logo.png) Data **flow**ground Connector

## Description

A generated **flow**ground connector for the Data API (version 1.2.0).

Generated from: https://api.apis.guru/v2/specs/clever.com/1.2.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:02+03:00

## API Description

Serves the Clever Data API

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Returns a list of student contacts

*Tags:* `Contacts`

#### Input Parameters
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_

### Returns a specific student contact

*Tags:* `Contacts`

#### Input Parameters
* `id` - _required_

### Returns the district for a student contact

*Tags:* `Contacts`

#### Input Parameters
* `id` - _required_

### Returns the student for a student contact

*Tags:* `Contacts`

#### Input Parameters
* `id` - _required_

### Returns a list of district admins

*Tags:* `District Admins`

#### Input Parameters
* `starting_after` - _optional_
* `ending_before` - _optional_
* `show_links` - _optional_

### Returns a specific district admin

*Tags:* `District Admins`

#### Input Parameters
* `id` - _required_

### Returns a list of districts

*Tags:* `Districts`

### Returns a specific district

*Tags:* `Districts`

#### Input Parameters
* `id` - _required_
* `include` - _optional_

### Returns the admins for a district

*Tags:* `Districts`

#### Input Parameters
* `id` - _required_

### Returns the schools for a district

*Tags:* `Districts`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns the sections for a district

*Tags:* `Districts`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns the status of the district

*Tags:* `Districts`

#### Input Parameters
* `id` - _required_

### Returns the students for a district

*Tags:* `Districts`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns the teachers for a district

*Tags:* `Districts`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns a list of school admins

*Tags:* `School Admins`

#### Input Parameters
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns a specific school admin

*Tags:* `School Admins`

#### Input Parameters
* `id` - _required_
* `include` - _optional_

### Returns the schools for a school admin

*Tags:* `School Admins`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_

### Returns a list of schools

*Tags:* `Schools`

#### Input Parameters
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns a specific school

*Tags:* `Schools`

#### Input Parameters
* `id` - _required_

### Returns the district for a school

*Tags:* `Schools`

#### Input Parameters
* `id` - _required_

### Returns the sections for a school

*Tags:* `Schools`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns the students for a school

*Tags:* `Schools`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns the teachers for a school

*Tags:* `Schools`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns a list of sections

*Tags:* `Sections`

#### Input Parameters
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns a specific section

*Tags:* `Sections`

#### Input Parameters
* `id` - _required_

### Returns the district for a section

*Tags:* `Sections`

#### Input Parameters
* `id` - _required_

### Returns the school for a section

*Tags:* `Sections`

#### Input Parameters
* `id` - _required_

### Returns the students for a section

*Tags:* `Sections`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_

### Returns the primary teacher for a section

*Tags:* `Sections`

#### Input Parameters
* `id` - _required_

### Returns the teachers for a section

*Tags:* `Sections`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_

### Returns a list of students

*Tags:* `Students`

#### Input Parameters
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns a specific student

*Tags:* `Students`

#### Input Parameters
* `id` - _required_
* `include` - _optional_

### Returns the contacts for a student

*Tags:* `Students`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_

### Returns the district for a student

*Tags:* `Students`

#### Input Parameters
* `id` - _required_

### Returns the primary school for a student

*Tags:* `Students`

#### Input Parameters
* `id` - _required_

### Returns the sections for a student

*Tags:* `Students`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_

### Returns the teachers for a student

*Tags:* `Students`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_

### Returns a list of teachers

*Tags:* `Teachers`

#### Input Parameters
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_
* `where` - _optional_

### Returns a specific teacher

*Tags:* `Teachers`

#### Input Parameters
* `id` - _required_
* `include` - _optional_

### Returns the district for a teacher

*Tags:* `Teachers`

#### Input Parameters
* `id` - _required_

### Returns the grade levels for sections a teacher teaches

*Tags:* `Teachers`

#### Input Parameters
* `id` - _required_

### Retrieves school info for a teacher.

*Tags:* `Teachers`

#### Input Parameters
* `id` - _required_

### Returns the sections for a teacher

*Tags:* `Teachers`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_

### Returns the students for a teacher

*Tags:* `Teachers`

#### Input Parameters
* `id` - _required_
* `limit` - _optional_
* `starting_after` - _optional_
* `ending_before` - _optional_

## License

**flow**ground :- Telekom iPaaS / clever-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
