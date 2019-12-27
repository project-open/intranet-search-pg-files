# ]po[ Full-Text File Search
This package is part of ]project-open[, an open-source enterprise project management system.

For more information about ]project-open[ please see:
* [Documentation Wiki](http://www.project-open.com/en/)
* [V5.0 Download](https://sourceforge.net/projects/project-open/files/project-open/V5.0/)
* [Installation Instructions](http://www.project-open.com/en/list-installers)

About ]po[ Full-Text File Search:

<p><p><p>Provides full-text indexing for filenames and files in the ]po[ filestorages. Uses a number of external filters to periodically scan the ]po[ file storage for new files, builds up a Full Text Index and allows the user to retrieve the files using the normal search interface. 

# Online Reference Documentation

## Procedure Files

<table cellpadding="0" cellspacing="0"><tr valign="top"><td style="width:35%"><b><a href="http://www.project-open.net/api-doc/procs-file-view?version_id=98033&amp;path=packages/intranet-search-pg-files/tcl/intranet-search-pg-files-procs.tcl">tcl/intranet-search-pg-files-procs.tcl</a></b></td><td></td><td>File Search Library </td></tr></table>

## Procedures

<table cellpadding="0" cellspacing="0"><tr valign="top"><td style="width:35%"><b><a href="http://www.project-open.net/api-doc/proc-view?version_id=98033&amp;proc=im_package_intranet_pg_files_id">im_package_intranet_pg_files_id</a></b></td><td></td><td>Returns the package id of the intranet-search-pg-files module </td></tr><tr valign="top"><td style="width:35%"><b><a href="http://www.project-open.net/api-doc/proc-view?version_id=98033&amp;proc=intranet_search_pg_files_fti_content">intranet_search_pg_files_fti_content</a></b></td><td></td><td>Extract and normalize the file contents - using a best effort attempt using variuos filters </td></tr><tr valign="top"><td style="width:35%"><b><a href="http://www.project-open.net/api-doc/proc-view?version_id=98033&amp;proc=intranet_search_pg_files_index_all">intranet_search_pg_files_index_all</a></b></td><td></td><td>Index the entire server </td></tr><tr valign="top"><td style="width:35%"><b><a href="http://www.project-open.net/api-doc/proc-view?version_id=98033&amp;proc=intranet_search_pg_files_index_object">intranet_search_pg_files_index_object</a></b></td><td></td><td>Index the files of a single object such as a project, company or user. </td></tr><tr valign="top"><td style="width:35%"><b><a href="http://www.project-open.net/api-doc/proc-view?version_id=98033&amp;proc=intranet_search_pg_files_search_indexer">intranet_search_pg_files_search_indexer</a></b></td><td></td><td>Index the entire server. </td></tr></table>

## SQL Files

<table cellpadding="0" cellspacing="0"><tr valign="top"><td><b><a href="http://www.project-open.net/api-doc/display-sql?package_key=intranet-search-pg-files&amp;url=postgresql/intranet-search-pg-files-create.sql&amp;version_id=98033">sql/postgresql/intranet-search-pg-files-create.sql</a></b></td><td></td><td></td></tr><tr valign="top"><td><b><a href="http://www.project-open.net/api-doc/display-sql?package_key=intranet-search-pg-files&amp;url=postgresql/intranet-search-pg-files-drop.sql&amp;version_id=98033">sql/postgresql/intranet-search-pg-files-drop.sql</a></b></td><td></td><td></td></tr></table>

## Content Pages

<table cellpadding="0" cellspacing="0"><tr valign="top"><td><b>www/</b></td></tr><tr valign="top"><td style="width:35%"><b><a href="http://www.project-open.net/api-doc/content-page-view?version_id=98033&amp;path=packages/intranet-search-pg-files/www/index.adp">index.adp</a></b></td><td></td></tr><tr valign="top"><td style="width:35%"><b><a href="http://www.project-open.net/api-doc/content-page-view?version_id=98033&amp;path=packages/intranet-search-pg-files/www/index.tcl">index.tcl</a></b></td><td>Show files that are not indexed by the FTS</td></tr><tr valign="top"><td style="width:35%"><b><a href="http://www.project-open.net/api-doc/content-page-view?version_id=98033&amp;path=packages/intranet-search-pg-files/www/reindex-biz-object.tcl">reindex-biz-object.tcl</a></b></td><td>Show files that are not indexed by the FTS</td></tr></table>

