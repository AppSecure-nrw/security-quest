# Handling of Known Vulnerabilities on Request

Thousands of vulnerabilities are found in libraries every year. Most of the software that you run consists of such libraries. It is therefore important that libraries are kept up-to-date in order to take security updates with you in order to reduce the risk posed by these libraries.

## Activities

### Test Server Side Libraries Regarding Known Vulnerabilities

- tools/method
- usage
- treamtment

[OWASP Dependency Check](https://owasp.org/www-project-dependency-check/)
... andere tools
### Test Client Side Libraries Regarding Known Vulnerabilities
### Test Container Images Regarding Known Vulnerabilities
### Test for Default Credentials

## Risk

TODO

## Test for Value

Risiko * Zeit
Zielgruppe: gute Entwickler und/oder guter PO: Value = keine ungeplante Arbeit
Tagesergebnis: Security hat keinen Wert, weil es die Lead Time nicht beeinflusst.

TODO

Wenn die Lead Time (von Features) groesser wird, weil z.b. viel manueller Aufwand in die Aktivitaeten gesteckt wird ist dies schlecht. Vielleicht sollte man dann in die Folgeaktivitaet investieren.
Lead Time (von Features): Bei Folge-Capabilities kann die Lead Time besser werden

Lead Time (von Security Bugs): Wie lang ist ein Bug offen?

%C/A: Reduce of reword after implementing the capability (Measurable with Pentest)

Shift Left = increase %C/A downstream
increase %C/A downstream = less rework
less rework = improve lead time
--------------------------------------
Shift Left = improve lead time

https://cloud.google.com/architecture/devops/devops-process-work-visibility-in-value-stream
