#include $(top_srcdir)/Makefile.decl
NULL =

dbusconfdir = @DBUS_DIR@/system.d
dist_dbusconf_DATA = fso-msm-gps-activator.conf

dbusservicedir = @DBUS_SERVICE_DIR@/../system-services
dbusservice_in_file = org.freesmartphone.msmgps.service.in
dist_dbusservice_DATA = $(dbusservice_in_file:.service.in=.service)

CLEANFILES = $(dist_dbusservice_DATA)
MAINTAINERCLEANFILES = Makefile.in

