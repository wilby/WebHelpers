WebHelpers
==========

Web/Html Helper Class Library. Starting with StackExchange.DataExplorer.Helpers.HtmlUtilities which contains methods for converting Markdown to Html and Sanitizing Html

Basic Usage:


Santize / Normalize Html: @Html.Raw(HtmlUtilities.Safe(html)) 

// The Markdown RawToCooked Method allows Html insertion so you want to Sanitize 
// the input as you would any user input
Convert Markdown to Html: var html = HtmlUtilities.Safe(HtmlUtilities.RawToCooked(form["markdown"]))

