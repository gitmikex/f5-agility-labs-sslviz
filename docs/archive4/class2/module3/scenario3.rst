Scenario
--------

Your manager lets you know that the company's updated security policy requires the logging of usernames for all intercepted traffic. You are tasked with developing a working Proof of Concept and are asked to come up with an action plan to do so, with the following restrictions:

-  This process needs to be transparent to a user that has already authenticated to the domain (ex. is logged into a domain-joined computer)

Lab Overview
------------

This lab continues on from the work you already completed in the previous labs. You will configure SSL Orchestrator to enable NTLM authentication and provide the authenticated username to the Squid security service.

.. NOTE:: The Access Policy and associated authentication objects required for this lab have already been configured for you.