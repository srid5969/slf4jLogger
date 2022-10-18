# slf4jLogger

refference 
https://www.youtube.com/watch?v=8AN58dHzkz4

A level or severity is connected to a log event. It tells how important a log event is. In most logging frameworks you will find a common set of log levels and SLF4J is not different. The following log levels can be used when choosing the SLF4J as your logging library abstraction:

TRACE – log events with this level are the most fine-grained and are usually not needed unless you need to have the full visibility of what is happening in your application and inside the third-party libraries that you use. You can expect the TRACE logging level to be very verbose.
DEBUG – less granular compared to the TRACE level, but still more than you will need in everyday use. The DEBUG log level should be used for information that may be needed for deeper diagnostics and troubleshooting.
INFO – the standard log level indicating that something happened, application processed a request, etc. The information logged using the INFO log level should be purely informative and not looking into them on a regular basis shouldn’t result in missing any important information.
WARN – the log level that indicates that something unexpected happened in the application. For example a problem, or a situation that might disturb one of the processes, but the whole application is still working.
ERROR – the log level that should be used when the application hits an issue preventing one or more functionalities from properly functioning. The ERROR log level can be used when one of the payment systems is not available, but there is still the option to check out the basket in the e-commerce application or when your social media logging option is not working for some reason. You can also see the ERROR log level associated with exceptions.
If all these are new to you, check out our tutorial on log levels, where we explain in greater detail what they are and how to use them for efficient logging.
