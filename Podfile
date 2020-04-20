inhibit_all_warnings!
use_frameworks!
workspace 'ExampleCLI.xcworkspace'


abstract_target 'CommonAbs' do 

	pod 'SwiftyTimer', '~> 2.1'

	abstract_target 'CLIAppicationAbs' do
			platform :osx, '10.15'
		project 'CLIAppication/CLIAppication.xcodeproj'

		target 'CLIAppication' do 
		end
	end

	abstract_target 'CLIFrameworkAbs' do 
		platform :osx, '10.15'
		project 'CLIFramework/CLIFramework.xcodeproj'
		
		target 'CLIFramework' do 
			target 'CLIFrameworkTests' do 
			
			end
		end
	end

end