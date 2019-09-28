project 'HelloWorld/HelloWorld.xcodeproj'

platform :ios, '13.0'

abstract_target 'Hello' do
    use_frameworks!
    pod 'PromiseKit', '~> 6'
    pod 'Swinject', '~> 2'

    target 'HelloModel' do
    end

    target 'HelloModelTests' do
        inherit! :search_paths
    end

    target 'HelloWorld' do
    end

    target 'HelloWorldTests' do
        inherit! :search_paths
    end

    target 'HelloWorldUITests' do
        inherit! :search_paths
    end
end
